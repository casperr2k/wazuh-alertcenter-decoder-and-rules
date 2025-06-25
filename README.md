<h1><b>SearchInform AlertCenter decoders and rules for Wazuh</b></h1>

<h2><i>Integration with russian DLP system SearchInform for Wazuh</i></h2>

<h4><i>Installation:</i></h4>

1. <code>sudo cp 0228-alertcenter-decoders.xml /var/ossec/ruleset/decoders/</code>

2. <code>sudo cp 0228-alertcenter-rules.xml /var/ossec/ruleset/rules/</code>

3. <code>sudo chmod 640 /var/ossec/ruleset/decoders/0228-alertcenter-decoders.xml</code>

4. <code>sudo chmod 640 /var/ossec/ruleset/rules/0228-alertcenter-rules.xml</code>

5. <code>sudo chown root:wazuh /var/ossec/ruleset/decoders/0228-alertcenter-decoders.xml</code>

6. <code>sudo chown root:wazuh /var/ossec/ruleset/rules/0228-alertcenter-rules.xml</code>

7. <code>sudo systemctl restart wazuh-manager.service</code>
