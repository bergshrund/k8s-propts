| NAME     | PROMPT     | DESCRIPTION                  | EXAMPLE                            |
|----------|------------|------------------------------|------------------------------------|
| Pod      | create a pod with name app where image is gcr.io/k8s-k3s/demo:v1.0.0 and port 8000 has name http. Also add two labels app and run with value demo   | Single pod application manifest    | [app.yaml](yaml/app.yaml)|
|CronJon   | create a cronjob with name app-cronjob which will launch every 5 minutes hello container with bash script echoing phrase 'Hello world'| Simple CronJob manifest | [app-cronjob.yaml](yaml/app-cronjob.yaml)|
