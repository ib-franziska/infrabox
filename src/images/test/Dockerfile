FROM debian:9.5-slim

RUN    apt-get update -y \
    && apt-get install -y \
        python \
        python-pip \
        curl \
        git \
    && pip install \
        psycopg2 \
        nose \
        coverage \
        xmlrunner \
        mock \
        urllib3 \
        codecov \
        flask \
        flask_restplus \
        flask_socketio \
        ldap \
        requests==2.18.4 \
        PyJWT \
        jsonschema \
        cryptography \
        eventlet \
        boto3 \
        google-cloud-storage \
        future \
        bcrypt \
        pycrypto \
        azure-mgmt-resource \
        azure-storage \
        keystoneauth1==3.7.0 \
        python-swiftclient \
        bottle \
        python-cachetclient \
        six \
    && apt-get remove -y python-pip \
    && apt-get autoremove -y \
    && rm -rf /var/lib/apt/lists/*