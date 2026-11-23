> [!IMPORTANT]
> This repository is archived. fdk-nginx-enhetsregisteret-proxy-mock is deployed by Flux from
> [Informasjonsforvaltning/fdk-infra](https://github.com/Informasjonsforvaltning/fdk-infra/tree/main/apps/base/fdk-nginx-enhetsregisteret-proxy-mock);
> make changes there.

The goal of the proxy mock is provide local demo implementation of enhetsregisteret.
The data included in mock is corresponding to users declared in altinn mock

Demo:

```
#run proxy
docker-compose up -d nginx-enhetsregisteret-proxy-mock

#test
curl http://localhost:8132/enhetsregisteret/api/enheter/910244132
```