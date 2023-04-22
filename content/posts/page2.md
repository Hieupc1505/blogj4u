---
title: "Guid Of Loveit Hugo"
date: 2023-04-22T17:18:28+07:00
draft: fasle
tags: ["javascript", "es6"]
---

# hello every one

## admonition

{{< admonition type=example title="This is a tip" open=false >}}
A **tip** banner
{{< /admonition >}}
Or
{{< admonition tip "This is a tip" false >}}
A **tip** banner
{{< /admonition >}}

## Style

{{< style "text-align:right; strong{color:#00b1ff;}" >}}
This is a **right-aligned** paragraph.
{{< /style >}}

## Link

{{< link "https://assemble.io" >}}
Or
{{< link href="https://assemble.io" >}}

{{< link "mailto:contact@revolunet.com" >}}
Or
{{< link href="mailto:contact@revolunet.com" >}}

{{< link "https://assemble.io" Assemble >}}
Or
{{< link href="https://assemble.io" content=Assemble >}}

{{< link "https://github.com/upstage/" Upstage "Visit Upstage!" >}}
Or
{{< link href="https://github.com/upstage/" content=Upstage title="Visit Upstage!" >}}

## image

{{< image src="/images/avata.jpg" caption="Lighthouse (`image`)" src_s="/images/lighthouse-small.jpg" src_l="/images/lighthouse-large.jpg" >}}
{{< figure src="/images/avata.jpg" title="Lighthouse (figure)" >}}

## person

{{< person url="/images/avata.jpg" name="Evgeny Kuznetsov" nick="nekr0z" text="author of this shortcode" picture="https://evgenykuznetsov.org/img/avatar.jpg" >}}

{{< person "https://dillonzq.com/" Dillon "author of the LoveIt theme" >}}
{{< highlight html >}}

<section id="main">
    <div>
        <h1 id="title">{{ .Title }}</h1>
        {{ range .Pages }}
            {{ .Render "summary"}}
        {{ end }}
    </div>
</section>
{{< /highlight >}}
