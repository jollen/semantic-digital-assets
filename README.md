# Digital Assets in the Semantics Web

A simple project to address the semantics web technologies for digital assets management.

## Usage

Add ```bitmark-assets.js``` in your web page.

```
<script src="bitmark-assets.js"></script>
```

And link a photo copyrighted through bitmark blockchain.

```
<span resource="424d4b302cc97d8536a9c790b7b6c15f3d3503a31350344cefd1ec487df53a35ccab3beb" type="image"></span>
```

## Future work

To use the semantics web for bitmark digital assets management.

```
<rdf:RDF>
	<rdf:Description about="http://bitmark.com/asset/image">
		<p:image resource="424d4b302cc97d8536a9c790b7b6c15f3d3503a31350344cefd1ec487df53a35ccab3beb" />
	</bitmark>
</rdf:RDF>
```
