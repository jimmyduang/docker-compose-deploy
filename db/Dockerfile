FROM postgres:alpine
# 这个脚本只有在data目录没有数据的情况下才会执行
# This script will only be executed if there is no data in the data directory
COPY ./ /docker-entrypoint-initdb.d/