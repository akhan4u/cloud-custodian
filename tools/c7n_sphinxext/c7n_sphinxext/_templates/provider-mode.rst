.. File Generated By c7n-sphinxext from source. Do not edit.

.. _{{provider_name}}_modes:

{{provider_name}} Execution Modes
---------------------------------

{% for m in modes %}

{{ename(m)}}
{{underline(ename(m), '+')}}
{{edoc(m)}}
{{eschema(m)}}

{% endfor %}
