To install:

`docker pull matentzn/pheno-workbench-docker`

Run in background (needs quite a bit of memory to run smoothly):

`docker run -i -t -p 8080:8080 -e JAVA_OPTS='-Xms2G -Xmx8G' matentzn/pheno-workbench-docker`

Access app:

[http://localhost:8080/browser-0.0.1/](http://localhost:8080/browser-0.0.1/) in web browser (Chrome, Firefox, Edge, Opera)

Stop:
Hit ctrl+c in terminal.
