# Bookinfo Detail Service
Detail service has been developed on Ruby

## License
MIT License

## How to run

```bash
ruby details.rb 8080
```
## How to run with Docker

```bash
# Build Docker Image for Detail service
docker build -t details .

# Run details service on port 8081
docker run -d --name details -p 8081:8081 details
```
* Test with path `/details` and `/health`


## Website
[Opsta (Thailand) Co., Ltd.](https://www.opsta.co.th)
