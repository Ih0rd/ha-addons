FROM diegosouzapw/omniroute:3.8.7

# Persist data through HA Supervisor's /data mount
RUN rm -rf /app/data && ln -s /data /app/data

EXPOSE 20128
