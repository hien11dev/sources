## Install php from source
```
sudo apt install -y pkg-config build-essential autoconf bison re2c \ 
libbz2-dev libcurl4-openssl-dev libffi-dev libzip-dev libpng-dev libjpeg-dev \
libwebp-dev libavif-dev libgmp-dev libc-client-dev libkrb5-dev libldap2-dev \
libonig-dev libssl-dev libpq-dev libpspell-dev libreadline-dev libsodium-dev libxml2-dev
```
```
git clone https://github.com/php/php-src.git --branch=PHP-7.4.30 && \
cd php-src 
```
sudo ./buildconf
```
sudo ./configure \
--prefix=/etc/php/7.4 \
--enable-bcmath \
--with-curl \
--enable-exif \
--with-ffi \
--enable-ftp \
--enable-gd \
--with-webp \
--with-jpeg \
--with-webp \
--with-imap \
--with-imap-ssl \
--with-kerberos \
--enable-intl \
--with-ldap \
--enable-mbstring \
--with-openssl \
--with-pdo-mysql \
--with-pspell \
--with-readline \
--enable-sockets \
--with-sodium \
--enable-soap \
--with-libxml \
--with-fpm-user=www-data \
--with-fpm-group=www-data \
--with-mysql-sock \
--with-mysqli \
--with-pdo-mysql \
--with-pgsql \
--with-xsl \
--with-zlib
```

