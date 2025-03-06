# Gui's ESPHome Configs

A collection of configuration files for various ESPHome devices I own.

### Running a Configuration

To compile and upload a configuration to ESP device:

```bash
# Basic usage
esphome run configs/esphome-config.yml
```

### Viewing Logs

To view the real-time logs from your ESPHome device:

```bash
# Connect to device logs using the config file
esphome logs configs/esphome-config.yml

# Connect to logs on a specific IP address
esphome logs 192.168.1.xxx
```

### Dashboard

For a graphical interface to manage devices:

```bash
esphome dashboard .
```

Then open your browser to http://localhost:6052

## Security

`secrets.yaml` Is used for sensitive bits
