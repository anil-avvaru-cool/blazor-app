# Blazor Overview

## Component based architecture

## Server side/Client side rendering

## Web apps/Native apps

## Razor page
Razor is combination of HTML and C# directives like @page, @code etc

## Component parameter
````cs
[Parameter]
public int IncrementAmount { get; set; } = 1;
````

## Component calling with parameter
````cs
<Counter IncrementAmount="10" ></Counter>
````

## Event handling
````cs
<button class="btn btn-primary" @onclick="IncrementCount">Click me</button>
````






















