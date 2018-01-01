FROM homeassistant/home-assistant:0.60

RUN pip3 install --no-cache-dir PyChromecast==1.0.3

CMD [ "python", "-m", "homeassistant", "--skip-pip", "--config", "/config" ]
