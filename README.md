# Nuxeo scan push

## Description

Ce projet vise à  router les documents numérisés depuis des copieurs connectés au réseau vers la plateforme de gestion électronique de documents Nuxeo.

This project aims to route documents from network scanners to Nuxeo ECM platform.

## Features

Nuxeo Scan Push comes up with two modules 

 - [nxpush-server](https://subversion.univ-lille2.fr/gitlab/78232/nxpush-server/tree/master) contains all needed contribs to make it work on the Nuxeo side.
 - [nxpush-client](https://subversion.univ-lille2.fr/gitlab/78232/nxpush-client/tree/master) provides scanners with an HTTP proxy that make commmunication available with the Nuxeo platform.

## Requirement

 - Nuxeo 5.8 LTS
 - A Linux SMP/FTP server 

For more info see each module documentation

## Installation

For more info see each module documentation

## Configuration

 - Scanners have to be configured to send documents on a remote folder 
 - nxpush-client has to be configured to probe this folder on the Linux server

For more info see each module documentation



