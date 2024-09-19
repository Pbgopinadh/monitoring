# Monitoring

Monitoring is to get the insights of the performace and beahviour of the infrastructure/application.

APM tools: Application monitoring tools 
Infrastructure monitoring tools : promethues

4 golden signals for SRE : https://sre.google/sre-book/monitoring-distributed-systems/#:~:text=The%20four%20golden%20signals%20of,system%2C%20focus%20on%20these%20four.

NOC team

1.) Latency
2.) traffic
3.) Erros
4.) saturation

promethues require a agent running on the node machine to get the data.

so we require a dedicated machine where the promethues is installed.
Agents are installed on the machines which we want to monitor and these will send the metrics to the master machine for visbilty.

so depending upon the metrics we want we should install the required type of exporter.

so there are many exporters to provide us with various metrics for specific machines.

Promethues: there will be no authentication when accessing the GUI of the promethues as it doesnt provide any information.

for any application/software we are installing it is required to install with a service account/user profile.

