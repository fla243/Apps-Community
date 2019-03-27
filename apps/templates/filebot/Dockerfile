
FROM jlesage/filebot:v1.2.0

COPY License.class /opt/filebot/patch/net/filebot/License.class

RUN add-pkg zip && cd /opt/filebot/patch && zip -u /opt/filebot/jar/filebot.jar net/filebot/License.class
