FROM postgres:9.4
MAINTAINER LHX

# add the seed data to open_lmis
ENV POSTGRES_HOST trainingdb
ENV POSTGRES_DB open_lmis
ENV POSTGRES_USER openlmis
ENV POSTGRES_PASSWORD hello123

#the file dumpForTraining.sql must add manually
COPY dumpForTraining.sql /docker-entrypoint-initdb.d/

