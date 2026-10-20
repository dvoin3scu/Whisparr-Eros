# hotio's Whisparr image for the same upstream release, with the patched Whisparr.Core.dll and
# Whisparr.Api.V3.dll swapped in.
ARG BASE_IMAGE
FROM ${BASE_IMAGE}
COPY Whisparr.Core.dll Whisparr.Api.V3.dll /app/bin/
