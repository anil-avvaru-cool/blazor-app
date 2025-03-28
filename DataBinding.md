# Data binding
@bind defaults to onchange
@bind:event Any event like oninput
@bind:after Fires after the event fires

````cs

<input @bind="@textBinding1" @bind:event="oninput" @bind:after="Search" > 
````