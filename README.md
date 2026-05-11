# devops intern final project
## Name:
Faith Amenawon Izebhor

## Date:
2026-05-11

## Project Overview: 
This project demonstrates a full DevOps workflow using:

- Git & GitHub
- Linux scripting
- Docker
- GitHub Actions CI/CD
- Nomad deployment
- Loki monitoring

  ## How to run

  ### python App
  python hello.py

  ### Docker
  docker build -t hello-devops
  docker run hello-devops

  ### Script
  chmod +x scripts/sysinfo.sh
  ./scripts/sysinfo.sh

  ### CI/CD
  Push to GitHub main branch

  ### Nomad
  nomad job run nomad/hello.nomad

  ## CI Badge
![CI](https://github.com/devfadora/devops-intern-final/actions/workflows/ci.yml/badge.svg)
