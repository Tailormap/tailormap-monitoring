FROM grafana/grafana:11.5.2
# alternatively use grafana/grafana-enterprise
# or
# docker pull grafana/grafana-oss
# see https://grafana.com/docs/grafana/latest/installation/docker/#run-the-grafana-main-branch

ARG GF_INSTALL_PLUGINS

# Add provisioning
ADD ./provisioning /etc/grafana/provisioning

# see https://github.com/grafana/grafana/blob/main/packaging/docker/Dockerfile#L76
USER "$GF_UID"
