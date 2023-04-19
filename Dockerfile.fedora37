FROM fedora:37

# Install base packages
RUN dnf install -y \
    bash \
    coreutils \
    curl \
    diffutils \
    gcc \
    git \
    make \
    patch \
    python \
    rpm-build \
    rpm-devel \
    rpmdevtools \
    rpmlint \
    wget \
    && dnf clean all \
    && rm -rf /var/cache/dnf

# Install rpm macros

RUN dnf install -y \
    cmake-rpm-macros.noarch \
    fedora-rpm-macros \
    go-rpm-macros \
    kernel-rpm-macros \
    lua-rpm-macros \
    lua-rpm-macros \
    pyproject-rpm-macros \
    python-rpm-macros \
    python-srpm-macros \
    python3-rpm-macros \
    systemd-rpm-macros \
    typelib-srpm-macros \
    && dnf clean all \
    && rm -rf /var/cache/dnf
