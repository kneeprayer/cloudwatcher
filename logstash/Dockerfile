FROM logstash:5
MAINTAINER kneeprayer <kneeprayer@gmail.com>

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
RUN logstash-plugin install logstash-input-cloudwatch
COPY ./conf /etc/logstash/conf.d