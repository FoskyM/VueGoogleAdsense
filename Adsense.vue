<template>
	<ins class="adsbygoogle"
		:data-ad-client="adClient"
		:data-ad-slot="adSlot"
		:data-ad-format="adFormat"
		:style="adStyle"
		:data-full-width-responsive="responsive"></ins>
</template>

<script>
export default {
	name: 'Adsense',
	props: {
		adClient: {
			type: String,
			required: true
		},
		adSlot: {
			type: String,
			required: true
		},
		adFormat: {
			type: String,
			required: false,
			default: 'auto'
		},
		adStyle: {
			type: String,
			required: false,
			default: 'display: block'
		},
		responsive: {
			type: String,
			required: false,
			default: 'false'
		}
	},
	mounted() {
		(window.adsbygoogle = window.adsbygoogle || []).push({})
	}
}
</script>
