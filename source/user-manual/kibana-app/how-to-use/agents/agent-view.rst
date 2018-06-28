.. Copyright (C) 2018 Wazuh, Inc.

.. _agent_view:

Agent view
==========

Similar to Overview, when you select an agent from the agents list you can check alerts and configuration for that agent specifically.

Agent status
------------

At the very top of the agent view you'll see its ID, name and status.

.. thumbnail:: ../../../../images/kibana-app/agents/agent-view-1.png
    :title: agent-view-1
    :align: center
    :width: 50%

Agent tabs bar
--------------

An agent view is very similar to the Overview tab, the main difference being visualizations are applying an additional
filter related to the agent ID itself, this way we can filter data from this specific agent. The current tab is underlined.

.. thumbnail:: ../../../../images/kibana-app/agents/agent-view-5.png
    :title: agent-view-5
    :align: center
    :width: 100%


Switching between agents
------------------------

You'll able to quick change agent using the autocomplete from the top right corner of any agent tab.

.. thumbnail:: ../../../../images/kibana-app/agents/agent-view-3.png
    :title: agent-view-3
    :align: center
    :width: 70%

Searching data from Elasticsearch
---------------------------------

You can use the search bar, which uses Lucene syntax, to execute custom queries. The results will be applied to the visualizations.

.. thumbnail:: ../../../../images/kibana-app/agents/agent-view-2.png
    :title: agent-view-2
    :align: center
    :width: 100%

Example of visualizations you can see:

.. thumbnail:: ../../../../images/kibana-app/agents/agent-view-4.png
    :title: agent-view-4
    :align: center
    :width: 100%

Agent configuration
-------------------

Since an agent always is included into a Wazuh group, you'll be able to see its applied configuration under the configuration tab.

.. thumbnail:: ../../../../images/kibana-app/agents/config-1.png
    :title: config-1
    :align: center
    :width: 100%

Also, you can see the raw content of the agent configuration.

.. thumbnail:: ../../../../images/kibana-app/agents/config-2.png
    :title: config-2
    :align: center
    :width: 100%

More information
----------------

https://documentation.wazuh.com/current/user-manual/agents/index.html
