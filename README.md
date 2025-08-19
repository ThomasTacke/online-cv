# online-cv

My online CV.

## Run Locally

```shell
poetry run mkdocs serve -f config/de/mkdocs.yml
poetry run mkdocs serve -f config/en/mkdocs.yml
```

## Poetry

### Update Packages

```shell
poetrty update
```

## Podman

```shell
sudo podman build -f Dockerfile -t local-test .
```

```shell
sudo podman run -p 80:80 local-test
```

## Docker

```shell
sudo docker build -f Dockerfile -t local-test .
```

```shell
sudo docker run -p 80:80 local-test
```

