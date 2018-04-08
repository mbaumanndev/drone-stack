Drone Stack
==========

This is my sample Drone Stack, I will improve it with my needs.

Here is a sample `.env` file :

```
DRONE_VERSION=0.8
DRONE_HOST=https://your-host.com
DRONE_GITHUB_CLIENT=<your gh oauth client>
DRONE_GITHUB_SECRET=<your gh oauth secret>
DRONE_SECRET=<your drone secret, a randon string>
AUTHORIZED_USERS=<your authorized users, comma separated>
```

Just `docker-compose up -d` and you are good to go !
