# Testing out Kubernetes with Skaffold

Here I was just testing out how to use Kubernetes with Skaffold. 
I used minikube and kubectl at local development.
I also setup a little CI/CD with GitHub -> Travis -> DockerHub for faster workflow (also I actually really like it, seems so easy and it is :D )

I deployed images from DockerHub in minikube cluster and set them together with ClusterIP services and for routing with outside world I used nginx-ingress. For better development I used Skaffold for changes inside (docker)images.

While just testing this out and playing it with little I also used a book, that book is "Kubernetes: Up and Running: Dive Into the Future of Infrastructure" and I also used different resources from google, like always.

For a guy who has not worked with networking and devops alot it was complicated but Up and Running book helped me and I learned alot, also...GOOGLE!!!