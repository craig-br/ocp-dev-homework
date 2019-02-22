FROM registry.redhat.io/openshift3/jenkins-agent-maven-35-rhel7:v3.11
USER root
RUN yum -y install skopeo && yum clean all
USER 1001
