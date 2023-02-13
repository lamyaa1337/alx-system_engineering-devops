#!/bin/bash

echo "Theaabsolute path of the current working directory is:"
echo "$(cd "$(dirname "$0")"; pwd -P)"

