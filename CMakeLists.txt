# Copyright (c) 2013-2014 Plenluno All rights reserved.

cmake_minimum_required(VERSION 2.8)

project(httpparser)

add_library(httpparser STATIC
   	http_parser.c
)
