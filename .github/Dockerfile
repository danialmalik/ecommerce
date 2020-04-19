FROM edxops/ecommerce:ironwood.master

RUN apt-get update && \
    apt-get install -y \
    libstartup-notification0 \
        firefox \
        xvfb

ENV TRAVIS=1
ENV DJANGO_SETTINGS_MODULE=ecommerce.settings.test
