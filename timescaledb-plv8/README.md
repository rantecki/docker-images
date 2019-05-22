TimescaleDB's official Docker image is based off the alpine Postgres image,
which makes it very hard to install additional extensions, such as PLV8. My
workaround is to install Timescaledb on top of an existing (debian-based)
Postgres image with PLV8 already installed.
