# Runtastic archiver [![Build Status](https://travis-ci.org/Metalnem/runtastic.svg?branch=master)](https://travis-ci.org/Metalnem/runtastic) [![Go Report Card](https://goreportcard.com/badge/github.com/metalnem/runtastic)](https://goreportcard.com/report/github.com/metalnem/runtastic) [![license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://raw.githubusercontent.com/metalnem/runtastic/master/LICENSE)
Command line tool to archive all your Runtastic activities.

## Downloads

[Windows](https://github.com/Metalnem/runtastic/releases/download/v1.2.0/runtastic-cli-win64-1.2.0.zip)  
[Mac OS X](https://github.com/Metalnem/runtastic/releases/download/v1.2.0/runtastic-cli-darwin64-1.2.0.zip)

## Usage

```
$ ./runtastic-cli
Usage of ./runtastic:
  -email string
    	Email (required)
  -format string
    	Optional export format (gpx, tcx or kml) (default "gpx")
  -password string
    	Password (required)
```

## Example

```
$ ./runtastic -email user@example.org -password secret123 -format gpx
```
