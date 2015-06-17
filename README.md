# org.dita-community.xhtml-adjct
Use the adjust-copy-to preprocessing extension with the base XHTML transform

This plugin does nothing except call the XHTML transform but with the dc-preprocess
Ant target used in place of the base preprocess Ant target. This has the effect
of applying the adjust-copy-to (and any other preprocessing extensions) to 
the XHTML.

Requires the org.dita-community.preprocess-extensions, org.dita-community.adjust-copy-to,
and org.dita-community.common.xslt plugins.

See the org.dita-community.adjust-copy-to project's readme.md file for details.

NOTE: This plugin will only work with the 1.8.5 Open Toolkit.