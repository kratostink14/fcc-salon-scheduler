# Salon Appointment Scheduler

Interactive terminal application for booking salon services, built with Bash and PostgreSQL.
Developed for the [freeCodeCamp Relational Database Certification](https://www.freecodecamp.org/learn/relational-database/).

## Features
- Interactive Bash CLI
- PostgreSQL relational database
- Automated customer registration

## Database Schema
- `customers`: name, phone (unique)
- `services`: available treatments
- `appointments`: link between customers and services at a specific time

## Usage
1. Restore database: `psql --username=freecodecamp salon < salon.sql`
2. Run script: `./salon.sh`
