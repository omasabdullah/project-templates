# Project Templates
I'm sick of installing packages in my local computer so I began to code exclusively in docker containers. These folders help me create projects exclusively in docker containers.

## Projects

### Rails
Copy the files to a folder of your choice and execute the following commans:

1. Generate a new rails project
```bash
docker-compose run web rails new . --force
```
2. Run the rails server
```bash
docker-compose up
```
