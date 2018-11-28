
FROM python:slim-stretch

# Install Azure Event Hub PythonSDK Module
RUN pip install azure-eventhub

# Remove Unneeded PIP Cache after Install
RUN rm -rf /.cache

RUN apt-get autoremove -o APT::Autoremove::RecommendsImportant=0 -o APT::Autoremove::SuggestsImportant=0