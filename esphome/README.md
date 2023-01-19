# How To Update Bulbs

## Update with Command Line:

### Install Dependencies

1. [Python](https://www.python.org/)
2. [ESPHome](https://esphome.io/guides/getting_started_command_line.html): `python3 -m pip install esphome`

### Step-By-Step

```bash
# navigate to this esphome directory
cd ~/lalt-automation/esphome

# run esphome on every house light bulb
esphome run --no-logs house_light_*.yaml

# alternatively run esphome on a single bulb
esphome run house_light_1.yaml
```

## Update with Home Assistant:

https://esphome.io/guides/getting_started_hassio.html
