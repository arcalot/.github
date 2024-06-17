# Arcalot
<a href="https://arcalot.io"><img align="right" width="200px" style="padding-left: 2em;"
 alt="Arcalot logo showing a shield with the Arcalot inscription on a hill with the 
 silhouette of a castle in the background" 
 src="https://github.com/arcalot/.github/raw/main/branding/arcalot.png"></a>

The Arcalot community is dedicated to developing modular tools, plugins, and libraries
with flexible implementations to be used independently or as complete end-to-end
solutions. We believe in enabling automation and portability of complex tasks and in
pre-validating actions to avoid costly re-runs due to late failures and incompatible
data.

<br clear="right"/>

# Arcaflow

<a href="https://arcalot.io/arcaflow"><img align="left" width="200px"
style="padding-right: 2em; padding-bottom: 2em;" alt="Arcaflow logo showing a waterfall and a river with 3
trees symbolizing the various plugins"
src="https://github.com/arcalot/.github/raw/main/branding/arcaflow.png"></a>

Arcaflow is a workflow system consisting of three main components:

* [The Arcaflow engine](https://github.com/arcalot/arcaflow-engine), statically-compiled
and platform-portable, written in Go
* [Plugins](https://github.com/orgs/arcalot/repositories?q=arcaflow-plugin-), written in
various languages and delivered as Linux containers or modules
* [Workflow definitions](https://github.com/arcalot/arcaflow-workflows), written in
YAML, tying together plugins and their data

<br clear="left"/>

Arcaflow is highly-flexible and portable, helping you to build
pipelines of actions via plugins. Plugin steps typically perform one action well, 
creating or manipulating data that is returned in a machine-readable format. Data is
validated according to schemas as it passes through the pipeline in order to clearly
diagnose type mismatch problems early. Arcaflow runs on your laptop, a jump host, or in
a CI system, requiring only the Arcaflow engine binary, a workflow definition in YAML,
and a compatible container runtime.

Arcaflow allows you to encapsulate and version-control expertise, making potentially
very complex workflows easily portable among environments and automation systems. With
an Arcaflow workflow, you can carefully craft a pipeline of actions that serves your
direct needs and share that worflow virtually unchanged for others to run in different
environments and CI/CD systems.

An ever-growing catalog of
[official plugins](https://github.com/orgs/arcalot/repositories?q=arcaflow-plugin-) are
maintained within the Arcalot organization and are available as
[versioned containers from Quay.io](https://quay.io/organization/arcalot). You can also
build your own containerized plugins using the the Arcaflow SDK, available for
[Python](https://arcalot.io/arcaflow/creating-plugins/python/) and
[Golang](https://github.com/arcalot/arcaflow-plugin-sdk-go). We encourage you to
contribute your plugins to the community, and you can start by adding them to the
[plugins incubator](https://github.com/arcalot/arcaflow-plugins-incubator) repo via a
pull request.

![image](https://raw.githubusercontent.com/arcalot/arcaflow-engine/version-and-flags/arcaflow-basic-demo.gif)

# Documentation

We work hard to bring the documentation to the user, meaning that you should fine a lot
of relevant documentation in the context of what you may be working on via readme files,
be it the engine, the SDK, a plugin, a workflow, or a sub-component. Exhaustive
documentation, developer guides, and getting started info will always be located in the
[arcalot.io](https://arcalot.io) pages.

# Community

We invite you to contribute! Check out the issues in the individual repositories for
ideas on where to get involved, or consider contributing a new plugin by starting with
our [python plugin template repository](https://github.com/arcalot/arcaflow-plugin-template-python).
Outside contributions and pull requests are of course always welcome.

If you want to get more involved with contributions, maintenance, and governance,
consider joining the
[Arcalot Round Table](https://github.com/arcalot/arcalot-round-table) (ART), our central
community body. The ART currently holds bi-weekly video conference meetings. Please
reach out to one of our
[ART chairs](https://github.com/arcalot/arcalot-round-table/blob/main/ART_MEMBERS.md)
for more information.

You can find our general community health files like our code of conduct and
contribution guidelines in the [.github repository](https://github.com/arcalot/.github).
If you have any questions or suggestions, please use the issues in the respective
repository.