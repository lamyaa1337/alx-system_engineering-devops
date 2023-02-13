#!/bin/bash
echo "Theabsolute path od the working directory is :"
echo "$(cd "$(dirname "$0")"; pws -P)"
