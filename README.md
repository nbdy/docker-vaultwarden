# docker-glpi

Run a [vaultwarden](https://github.com/dani-garcia/vaultwarden) as a docker container via docker compose.

Edit the docker-compose.yml and run `docker compose up`.

If you want to disable sign-ups, run the container once with sign-ups enabled and create your main user.<br>
After you have created your user stop the container, disable sign-ups and run `docker compose up` again.<br>
Now you can sign in and invite all your friends and family.
