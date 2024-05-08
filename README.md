<h1>Skeleton Loading KMP</h1>
  <img src="https://github.com/mrjafari-dev/skeleton-loading-effect/blob/main/video/ezgif-7-2598505f6b.gif" width="80%"/>
<p>The <code>ShimmerLoader</code> Composable function creates a shimmer loading animation using Jetpack Compose. It simulates a loading effect commonly seen in mobile and web applications while content is being fetched or processed.</p>

<h2>How it works</h2>

<p>The <code>ShimmerLoader</code> Composable function utilizes Compose animation and coroutine functionalities to create a shimmering effect. Here's a brief overview of its implementation:</p>

<ul>
        <li>It defines a <code>shimmerState</code> variable to track the loading state.</li>
        <li>It uses an <code>InfiniteTransition</code> to animate the shimmer effect continuously.</li>
        <li>It launches a coroutine to simulate a loading delay and updates the <code>shimmerState</code> accordingly.</li>
        <li>It creates a <code>Card</code> with a rounded corner shape, containing a <code>Box</code> with a gradient background to achieve the shimmer effect.</li>
</ul>

<h2>Usage</h2>

<p>To use the <code>ShimmerLoader</code> Composable function in your Jetpack Compose project, follow these steps:</p>

<ol>
        <li>Copy the <code>ShimmerLoader</code> function into your project.</li>
        <li>Use the <code>ShimmerLoader</code> function in your Composable UI by calling it and passing any necessary modifiers.</li>
        <li>Customize the appearance and behavior of the shimmer loader by adjusting parameters such as duration, colors, and shapes as needed.</li>
</ol>

<h2>Example</h2>

<p>Here's an example of how you can use the <code>ShimmerLoader</code> Composable function in your Compose UI:</p>

<pre><code>@Composable
fun MyScreen() {
    Column(
        modifier = Modifier.fillMaxSize(),
        verticalArrangement = Arrangement.Center,
        horizontalAlignment = Alignment.CenterHorizontally
    ) {
        Text(text = "Welcome to My App", style = MaterialTheme.typography.h5)
        Spacer(modifier = Modifier.height(16.dp))
        ShimmerLoader(modifier = Modifier.size(200.dp))
    }
}
</code></pre>

<p>This will display a shimmer loading animation below the "Welcome to My App" text.</p>
  <br/>
<br/>
