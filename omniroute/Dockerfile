FROM diegosouzapw/omniroute:3.7.8

# Persist data through HA Supervisor's /data mount
RUN rm -rf /app/data && ln -s /data /app/data

EXPOSE 20128
