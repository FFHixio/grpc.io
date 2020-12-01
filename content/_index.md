+++
title = "Docsy"
linkTitle = "Docsy"

+++

{{< blocks/cover image_anchor="top" height="full" color="primary" >}}
<img class="homepage__logo" src="/img/logos/grpc-logo.png" />

<p class="mb-3 display-2">
	A high performance, open source universal RPC framework
</p>
<a
	class="mx-auto mb-5 btn btn-primary font-weight-bold"
	href="/docs/what-is-grpc/introduction"
>
Learn more
</a>
<p class="mb-3 display-2 font-weight-normal">Get started!</p>
<div class="inline-block align-middle">
<a class="btn btn-primary">Go</a>
<a class="btn btn-primary">C++</a>
<a class="btn btn-primary">Java</a>
<a class="btn btn-primary">Python</a>
<a class="btn btn-primary">C#</a>
<a class="btn btn-primary">…</a>
{{< /blocks/cover >}}

{{% blocks/lead color="white" %}}

<h1 class="mb-3 display-1 text-primary">
	Why gRPC?
</h1>
<h3 class="font-weight-light">
	gRPC is a modern open source high performance RPC framework that can
	run in any environment. It can efficiently connect services in and
	across data centers with pluggable support for load balancing,
	tracing, health checking and authentication. It is also applicable
	in last mile of distributed computing to connect devices, mobile
	applications and browsers to backend services.
</h3>
{{% /blocks/lead %}}

{{< blocks/section color="100" type="section" >}}

<div class="row">
	<div class="d-inline-flex align-items-start col-12 col-md-6 mb-5">
		<img class="w-50 mr-5" src="/img/icons/feature-1.svg" alt="feature icon">
		<div>
			<p>Simple service definition</p>
			<p class="subtitle">
				Define your service using Protocol Buffers, a powerful binary serialization toolset and language
			</p>
		</div>
	</div>
	<div class="d-inline-flex align-items-start col-12 col-md-6 mb-5">
		<img class="w-50 mr-5" src="/img/icons/feature-2.svg" alt="feature icon">
		<div>
			<p>Start quickly and scale</p>
			<p class="subtitle">
				Install runtime and dev environments with a single line and also scale to millions of RPCs per second with the framework
			</p>
		</div>
	</div>
</div>
<div class="row">
	<div class="d-inline-flex align-items-start col-12 col-md-6">
		<img class="w-50 mr-5"  src="/img/icons/feature-3.svg" alt="feature icon">
		<div>
			<p>Works across languages and platforms</p>
			<p class="subtitle">
				Automatically generate idiomatic client and server stubs for your service in a variety of languages and platforms
			</p>
		</div>
	</div>
	<div class="d-inline-flex align-items-start col-12 col-md-6">
		<img class="w-50 mr-5" src="/img/icons/feature-4.svg" alt="feature icon">
		<div>
			<p>Bi-directional streaming and integrated auth</p>
			<p class="subtitle">
				Bi-directional streaming and fully integrated pluggable authentication with HTTP/2-based transport
			</p>
		</div>
	</div>
</div>
{{< /blocks/section >}}

{{< blocks/section color="white" type="section" >}}

<h1 class="mb-5 display-1 text-center text-primary">
	Used by
</h1>
{{< home/used-by >}}
{{< /blocks/section >}}

{{< blocks/section color="white" type="section" >}}

<h2 class="mb-5 display-2 text-center">
	gRPC is a <a href="https://cncf.io">Cloud Native Computing Foundation</a> incubation project
</h2>
<img class="w-50 mx-auto" src="/img/logos/cncf-horizontal-color.png" alt="Cloud Native Computing Foundation logo" />
{{< /blocks/section >}}
