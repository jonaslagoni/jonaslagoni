What have, and am I working on? 👀

# The projects 🔭

<table style="table-layout: fixed; width: 100%;">
  <tr>
    <td>
      <img src="https://github.com/user-attachments/assets/f1dd3b47-4481-42a4-ac8a-63d9547a5a01" alt="EventStack"/>
      <h1><a href="https://eventstack.tech">EventStack</a></h1><p>Is my company that develops software and offers consultancy and contract work around event-driven architectures and open source software.</p>
    </td>
    <td>
      <img src="https://github.com/user-attachments/assets/5a839f64-8ed3-49fe-84e2-899cbd7d5027" alt="The Codegen Project banner"/>
      <h1><a href="https://github.com/the-codegen-project/">The Codegen Project</a></h1><p>Is a next-gen code generator, that easily can be integrated into any project (regardless of language) that simplifies the implementation and testing phase - 100% open source.</td>
  </tr>
  <tr style="vertical-align: top;">
    <td>
      <img src="https://github.com/user-attachments/assets/7f7424be-d981-494d-9f50-8ed32a87198d" alt="GamingAPI banner"/>
      <h1><a href="https://github.com/GamingAPI/">GamingAPI</a></h1><p><a href="https://gamingapi.org/">GamingAPI.org</a> is a side project of mine where I try to use everything from AsyncAPI (tooling and spec) and incorporate it into a standard for interacting with all types of game servers (focus on <a href="https://rust.facepunch.com/">Rust</a>, upcoming Minecraft, etc.) through generated SDK's, documentation, governance, and more!</p>
    </td>
    <td>
      <img src="asyncapi.png" alt="AsyncAPI logo"/>AsyncAPI was a spare-time project turned full-time job at <a href="https://www.postman.com/">Postman</a> for an amazing 4 years and still engaged with the project. I am part of the <a href="https://www.asyncapi.com/community/tsc">AsyncAPI Technical Steering Committee</a>, release coordinator for v3, and maintainer and creator of a bunch of the <a href="https://github.com/orgs/asyncapi/repositories">open source tools</a> such as;</br>
      <ul>
        <li><a href="https://github.com/asyncapi/modelina">Modelina</a> a library I started with <a href="https://github.com/magicmatatjahu">Maciej</a> for generating models from various inputs (AsyncAPI, OpenAPI, JSON Schema, TypeScript models, etc) into various outputs (TypeScript, C#, Python, etc). Try it here <a href="https://modelina.org/playground">modelina.org/playground</a></li>
        <li><a href="https://github.com/asyncapi/EDAVisualiser/">EDAVisualiser</a> a visualization tool for simple and complex systems, which support all the major design frameworks, React, Next, Vue, Angular, etc. Try it here <a href="https://asyncapi.github.io/EDAVisualiser">asyncapi.github.io/EDAVisualiser</a></li>
        <li><a href="https://github.com/asyncapi/generator-react-sdk">React SDK</a> a contender to Nunjucks to render templates that could be anything. Read more here <a href="https://www.asyncapi.com/docs/tools/generator/react-render-engine">asyncapi.com/docs/tools/generator/react-render-engine</a></li>
      </ul>
    </td>
  </tr>
</table>

# Tooling
Here are all the tools I am actively maintaining;

- <h5>GH Action for bumping .NET versions</h5> <a href="https://github.com/jonaslagoni/gh-action-dotnet-bump">Automatically bump .NET/C# version</a> of libraries, by following semantic release.
- <h5>GH Action for bumping AsyncAPI documents</h5> <a href="https://github.com/jonaslagoni/gh-action-asyncapi-document-bump">Automatically bump the application version for AsyncAPI documents</a> by following semantic release.

<details>
  <summary>Here is a list of all the previous libraries and projects I have worked on.</summary>

- https://github.com/jonaslagoni/Wizard-Of-Treldan, university group project, 2d and 2 different UI games in one, with a custom game engine, written in Java.
- https://github.com/jonaslagoni/NEON, university group project, a 2d tower defense game, using OSGi to use a modular system to load and unload towers, maps, game modes, etc on the fly, build upon libgdx, written in Java.
- https://github.com/jonaslagoni/csgoLiveServer, spare time project trying to reflect what happens in a CSGO server in the web browser, first version of GamingAPI I guess.
- https://github.com/jonaslagoni/asyncapi-quicktype-template, AsyncAPI generator template to generate typed models with QuickType. 
- https://github.com/jonaslagoni/asyncapi-quicktype-filter, the core library code for the QuickType template.
- https://github.com/jonaslagoni/.NET-websocket-client-template, an old AsyncAPI generator template for generating a WebSocket wrapper in .NET.
- https://github.com/jonaslagoni/ts-websocket-server-template, an old AsyncAPI generator template for generating a WebSocket wrapper in TypeScript.
- https://github.com/jonaslagoni/Java-to-JSON-Schema, a JSON Schema draft-7 DSL for writing JSON Schema through code in Java. 
- https://github.com/jonaslagoni/Java-to-AsyncAPI, an AsyncAPI DSL for writing AsyncAPI documents through code in Java. Uses the JSON Schema variant as well internally to define payloads.
- https://github.com/asyncapi/dotnet-nats-template, an AsyncAPI template for generating .NET/C# NATS code, superseded by [The Codegen Project](https://github.com/the-codegen-project/cli/)
- https://github.com/asyncapi/ts-nats-template, an AsyncAPI template for generating TypeScript NATS code, superseded by [The Codegen Project](https://github.com/the-codegen-project/cli/)

</details>

## Writings
I am using [eventstack.tech/posts](https://eventstack.tech/posts) as my personal sanctuary for writing stuff about projects, updates, and different tech stuff.

Here is an overview of the subjects so far:
- Automated code generation ([introduction](https://eventstack.tech/posts/automated-utopia), [versioning](https://eventstack.tech/posts/automated-utopia-versioning), for [TypeScript libraries](https://eventstack.tech/posts/automated-utopia-typescript), for [.NET libraries](https://eventstack.tech/posts/automated-utopia-dotnet))
- AsyncAPI Governance ([getting started](https://eventstack.tech/posts/getting-started-with-governance), in practice [part 1](https://eventstack.tech/posts/enforcing-consistency-guidelines-part-1), [part 2](https://eventstack.tech/posts/enforcing-consistency-guidelines-part-2))
- API versioning ([theory](https://eventstack.tech/posts/versioning-is-easy), [in practice](https://eventstack.tech/posts/asyncapi-versioning-in-practice))
- [Reusability in AsyncAPI causing problems](https://eventstack.tech/posts/reusability-causing-problems)
- AsyncAPI tooling updates (week [30](https://eventstack.tech/posts/asyncapi-tooling-update-1), [33](https://eventstack.tech/posts/asyncapi-tooling-update-week-33), [39](https://eventstack.tech/posts/asyncapi-tooling-update-week-39), [46](https://eventstack.tech/posts/asyncapi-tooling-update-week-46))

## Conferences
This section is more for me than you, trying to keep track of what I am participating in or have.

<details>
  <summary>Here is a list of previous conferences and speaking arrangements in case you find it interesting.</summary>
  
- (speaking) APIDays conference Helsinki, 2024, in-person, gave a talk about `Navigating the jungle of the AsyncAPI Ecosystem`
- (speaking) AsyncAPI conference, at Sngular Madrid, 2023, in-person (watch the recording here: https://www.youtube.com/live/FN5eR1Zqh9c?si=A4gxOaJlHCg4ID3P&t=7038)
- (participating) AsyncAPI conference, at IBM London, 2023, in-person
- (speaking) APIDays Paris 2022, in-person, gave a talk about `AsyncAPI and schema format complexity`
- (participating) GOTO Copenhagen 2022, in-person
- (participating) Digital Transformation World, TMForum, Copenhagen 2022, in-person
- (speaking) AsyncAPI conference 2022, had two talks here. The two talks were `Next Generation of AsyncAPI` (watch the recording here: https://www.youtube.com/watch?v=WOMDYzHh-3w) and `The Intricacies of a Single Keyword in AsyncAPI` (watch the recording here: https://www.youtube.com/watch?v=fLAAXAXOGlE)
- (speaking) API:World 2021, online, talked about `How AsyncAPI can enhance your developer experience`
- (speaking) APIDays Interface 2021, online, talked about `How AsyncAPI can enhance your developer experience`. Watch the recording here: https://www.youtube.com/watch?v=W7L0ryT3Qmo
- (participating) Info Security Denmark 2021, in-person
- (participating) APIDays Paris 2019, in-person, invitation by [Fran](https://github.com/fmvilas)
- (participating) Info Security Denmark 2019, in-person

</details>
