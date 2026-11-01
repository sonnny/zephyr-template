edited for rp2040 only see west.yml

quick start:
  mkdir zep_app
  source ~/zephyrproject/.venv/bin/activate
  west init -m https://github.com/sonnny/zephyr-template.git
  west update

to build:
  west build -p -b rpi_pico app

