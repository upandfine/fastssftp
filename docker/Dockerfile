# Verwende das offizielle atmoz/sftp Basisimage
FROM atmoz/sftp:latest

# Füge eine Beispiel-Konfigurationsdatei hinzu
COPY /etc/users.conf /etc/sftp/users.conf

# Exponiere den Standard-SFTP-Port
EXPOSE 22

# Füge das Docker-Entry-Point-Skript hinzu
ENTRYPOINT ["/entrypoint"]

# Führe das SFTP-Daemon aus
CMD ["-D"]
