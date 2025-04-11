---
title: apps
descirption: these are the apps I'm hosting/trying out
template: splash
---
import { Card, CardGrid } from '@astrojs/starlight/components';

## Infrastructure

<CardGrid>
	<a class="card-link" href="/apps/dockage">
	<Card title="Dockage" icon="rocket">
		For managing my docker compose.
	</Card>
	</a>
	<a class="card-link" href="/apps/npm">
	<Card title="Nginx PM" icon="seti:db">
		For HTTPS and domain settings.
	</Card>
	</a>
	<a class="card-link" href="/apps/dashy">
	<Card title="Dashy" icon="cloudflare">
		Homepage.
	</Card>
	</a>
	<a class="card-link" href="/apps/uptime-kuma>
	<Card title="Uptime Kuma" icon="linux">
		Monitoring
	</Card>
	</a>
</CardGrid>

## Media
<CardGrid>
    <a class="card-link" href="apps/jellyfin">
    <card title="Jellyfin">
        For Media streaming
    </Card>
    </a>  
    <a class="card-link" href="apps/audiobooks">
    <card title="Audiobookshelf">
        For audiobook management
    </Card>
    </a>      
    <a class="card-link" href="apps/readarr">
    <card title="Readarr">
        For book and audiobook management
    </Card>
    </a>  
</CardGrid>