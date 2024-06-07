# Verwende das offizielle atmoz/sftp Basisimage
FROM atmoz/sftp:latest

# Füge eine Beispiel-Konfigurationsdatei hinzu
COPY /etc/users.conf /etc/sftp/users.conf

# Exponiere den Standard-SFTP-Port
EXPOSE 22


# Setze den EntryPoint auf das Standard-Entrypoint des Basisimages
ENTRYPOINT ["/entrypoint"]

# Führe den SSH-Daemon im Vordergrund aus
CMD ["/usr/sbin/sshd", "-D"]

