Then, we simply build the image and run docker.

docker build -t sosodocs .
docker run -itd -p 8089:8000 --rm sosodocs
And that is all, you should be able to navigate to http://127.0.0.1:8089 and see the documentation website running.
