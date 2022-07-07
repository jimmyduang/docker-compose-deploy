# 运行阶段指定scratch作为基础镜像
# Specify scratch as the base image during the run phase
FROM scratch
COPY ./srv-example /go/bin/srv-example
COPY ./config/ /go/bin/config/

EXPOSE 8081
WORKDIR /go/bin
CMD ["./srv-example"]
