FROM golang:1.19

ENV GO111MODULE=on
RUN go install github.com/AnshulMalik/webrtc/v3/examples/pion-to-pion/answer@latest

CMD ["answer"]

EXPOSE 50000
