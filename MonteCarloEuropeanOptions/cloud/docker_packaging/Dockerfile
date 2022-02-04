#
# Copyright (C) 2022 Intel Corporation
# SPDX-License-Identifier: Apache-2.0
#
FROM ubuntu:22.04
RUN apt-get update && apt-get install -y curl
WORKDIR /app
COPY start run MonteCarloInsideBlockingDP.avx* *.so* ./
CMD ["/bin/bash", "/app/start"]
