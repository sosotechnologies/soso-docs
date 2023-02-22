Then, we simply build the image and run docker.

docker build -t sosodocs .
docker run -itd -p 8089:8000 --rm sosodocs
And that is all, you should be able to navigate to http://127.0.0.1:8089 and see the documentation website running.

echo "# soso-docs" >> README.md
git init
git add README.md
git commit -m "Official mkdocs for sosotech"
git branch -M master
git remote add origin https://github.com/sosotechnologies/soso-docs.git
git push -u origin master