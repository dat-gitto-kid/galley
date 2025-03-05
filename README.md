# The-Galley
AOSP "Kitchen" for Docker; primarily created for building custom GrapheneOS builds

# Getting Started
1. `git clone https://github.com/dat-gitto-kid/galley` && `cd galley`
1.5. Modify docker-compose.yml and build.sh (for any mods, etc.) to your liking
2. `docker-compose -f docker-compose.yml up -d`
3. `docker logs the-galley # To monitor progress...`

Thanks to the GrapheneOS project, Magisk (https://github.com/topjohnwu/Magisk), and AVBRoot (https://github.com/chenxiaolong/avbroot)
