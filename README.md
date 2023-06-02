
# Containerized Website 

A HTML, CSS and JavaScript based website is Containerized using the nginx base image.

Website consists of a Drum Kit which can be play sounds on click and key press.



## Screenshots

![App Screenshot](https://github.com/Vinayakyadav27041/drum/blob/main/images/Drum%20Kit.jpg)


## Deployment

To deploy this project run using the image, pull the image using

```bash
  docker pull vinayakyadav27/web-container:latest-slim
```
then 

```bash
  docker run -d -p 80 [CONTAINER_ID]
```
then 

Check the port 80

```bash
  localhost:80
```


## Optimizations

After containerizing the Website the Container size was 25MB.

https://portal.slim.dev/home/xray/dockerhub.authenticated%3A%2F%2Frkcn.2IShT3HfCuK7YBw6V0pT54VgPtt%2Fvinayakyadav27%2Fweb-container%3Alatest#explorer


Then After Hardening the container on SlimAI the size was reduced to 7MB

https://portal.slim.dev/home/xray/dockerhub.authenticated%3A%2F%2Frkcn.2IShT3HfCuK7YBw6V0pT54VgPtt%2Fvinayakyadav27%2Fweb-container%3Alatest-slim%40sha256%3A94abb77bef5150b48d6f45642ec0d4a7a203ade70e17d5f2a151c6e8431b3bc7#explorer




Checking Webhook
