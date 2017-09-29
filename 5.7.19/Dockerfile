FROM mysql:5.7.19

RUN apt-get update && apt-get install -y --no-install-recommends \
	cron \
	&& rm -rf /var/lib/apt/lists/*

CMD ["cron", "-f"]
