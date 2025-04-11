---
title: homelab notes
descirption: so I don't have to reinvent the wheel every time I troubleshoot
template: splash
hero:
  tagline: I spend so much time doing homelab things now lol
  actions:
    - text: Apps
      link: /pages/apps/
---
import { Card, CardGrid } from '@astrojs/starlight/components';

## Categories

<CardGrid>
	<a class="card-link" href="/pages/apps/">
	<Card title="Apps & Services" icon="rocket">
		What I'm hosting.
	</Card>
	</a>
	<a class="card-link" href="/db/mariadb">
	<Card title="Databases" icon="seti:db">
		SQL/Database Notes.
	</Card>
	</a>
</CardGrid>