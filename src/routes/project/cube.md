---
index: 5
title: CSS Rubik's Cube
slug: project/cube
description: Verschillende HTML en CSS only experimenten met de wereldberoemde kubus.
image: /cube/banner.png
year: 2021
client: CMD Minor WebDev
link: [website, https://jonahgoldwastaken.github.io/css-rubiks-cube]
---

<script>
  import Image from '$lib/components/atoms/Image.svelte'
</script>

Voor het vak CSS To The Rescue mochten we de kracht CSS onderzoeken en
uitwerken in een van twee eindopdrachten. Een van de eindopdrachten was het
bouwen van een Rubik's Cube, en ik vond dat wel een mooie uitdaging.

Een van de mogelijke uitwerkingen in de eindopdracht was om de kubus
interactief te maken. Dit heb ik 2 weken lang geprobeerd uit te werken, maar
ben uiteindelijk tot de conclusie gekomen dat je interactiviteit niet 100%
werkend gaat krijgen zonder een soort geschiedenis van de draaiingen die
zijn gemaakt.

<Image lazy format="caption" src="/cube/interactive.png" caption="De kubus is zo interactief als CSS dat toelaat. Je krijgt wel grappige vormen door ermee te spelen!"/>

Verder heb ik geëxperimenteerd met animaties op basis van viewport size, de
grootte van de kubus veranderen op bredere schermen en heb ik een leuke
screensaver gemaakt.

<Image lazy format="caption" src="/cube/screensaver.png" caption="Een van de experimenten is een screensaver die (zeer hypnotiserend) op verschillende manieren over de pagina heen beweegt." />

Dit project was erg leerzaam voor mij omdat ik nu beter begrijp waar de
kracht van CSS ophoudt en het met JS aangevuld moet worden om de ervaring
compleet te maken. Ook heb ik veel nieuwe CSS selectoren geleerd, die veel
werk wat ik normaal met JS deed uit hand nemen. Nu weet ik zeker dat
Progressive Enhancement zo goed als altijd binnen handbereik ligt, en
accessibility van mijn projecten flink zullen stijgen.
