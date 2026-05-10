FROM microros/micro_ros_static_library_builder:jazzy

# Tools vorinstallieren (spart Zeit im Skript)
RUN apt-get update && apt-get install -y \
    gcc-arm-none-eabi \
    python3-vcstool \
    git \
    rsync \
    make \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /project