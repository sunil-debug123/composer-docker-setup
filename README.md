# Composer Docker Setup

This repository contains a Docker Compose-based setup that allows you to run Composer commands globally on your system. It uses the official Composer Docker image to make Composer accessible without needing to install it locally.

## Prerequisites

- Docker
- Docker Compose

## Setup

1. **Clone the repository:**

   Clone the repository to your local machine:

   ```bash
   git clone https://github.com/sunil-debug123/composer-docker-setup
   cd composer-docker-setup

   *Example*:
    docker-compose -f /Users/sunil/projects/composer-docker-setup/docker-compose.yml run --rm composer create-project drupal/recommended-project blacklight-collections-drupal --ignore-platform-req=ext-gd
   ```
