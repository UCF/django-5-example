# django-5-example
A containerized Django 5 template that works with Odo for development with live-reloading.

Ensure you have Podman and Odo installed. Then pull the repository and use the following command:

`ODO_PUSH_IMAGES=false odo dev --platform=podman --port-forward 8000:8000`

Now make a change in the Django app folder. Odo will track that change and live-reload the Django application.
