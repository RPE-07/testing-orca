# Gunakan image base resmi
FROM jenkins/jenkins:lts-jdk11

# Salin file plugins.txt
COPY plugins.txt /usr/share/jenkins/ref/plugins.txt

# --- PERBAIKAN DI SINI ---
# Gunakan jenkins-plugin-cli (pengganti install-plugins.sh)
RUN jenkins-plugin-cli --plugin-file /usr/share/jenkins/ref/plugins.txt
