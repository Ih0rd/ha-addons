FROM diegosouzapw/omniroute:latest

# Persist data through HA Supervisor's /data mount
RUN rm -rf /app/data && ln -s /data /app/data

EXPOSE 20128
