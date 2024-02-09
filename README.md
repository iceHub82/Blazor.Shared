<h1>Blazor Shared</h1>

<p dir="auto">Solution containing Blazor Server, Blazor Webassembly and Maui Blazor with a shared Razor component library with bare minimum setup to quickly get started with one component codebase for all three Blazor projects. Includes User authorization login for Maui Blazor </p>

<h2 dir="auto"><a id="user-content-getting-started" class="anchor" aria-hidden="true" tabindex="-1" href="#getting-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Getting Started</h2>

<p dir="auto">Quickly change the layout for all Blazor projects by editing the App.razor file in the Blazor.Razor.Shared Component library</p>

<pre><code>RouteView RouteData="@routeData" DefaultLayout="@typeof(Layout.MainLayout)"</code></pre>
