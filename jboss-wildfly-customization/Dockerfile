FROM jboss/wildfly
ADD customization /opt/jboss/wildfly/customization/
ADD modules /opt/jboss/wildfly/modules/

RUN /opt/jboss/wildfly/customization/execute.sh

ADD app.war /opt/jboss/wildfly/standalone/deployments/