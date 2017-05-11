# ulb
Scripts for use @ Université libre de Bruxelles

## Install

	make DESTDIR=/ PREFIX=/usr install

## Usage

	ulb <command> <...args>

### Check network connectivity

	ulb status network

### Check network authentication

	ulb status auth

### Authenticate once

	ulb auth once

### Authentication daemon

	ulb auth daemon
