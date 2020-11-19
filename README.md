dep_diverter
=====

A rebar plugin

Build
-----

    $ rebar3 compile

Use
---

Add the plugin to your rebar config:

    {plugins, [
        {dep_diverter, {git, "https://host/user/dep_diverter.git", {tag, "0.1.0"}}}
    ]}.

Then just call your plugin directly in an existing application:


    $ rebar3 dep_diverter
    ===> Fetching dep_diverter
    ===> Compiling dep_diverter
    <Plugin Output>
