# Snort IDS Lab

Academic intrusion-detection lab using Snort on a network you control. The included rule is a harmless example that alerts on an HTTP request containing a test marker.

## Files
- `rules/local.rules`: local demonstration rule.
- `docs/lab.md`: safe lab workflow and validation notes.

## Use
Copy the rule into your local Snort rules file or include it in your lab configuration, then validate using the configuration syntax supported by your Snort version. Test only on traffic generated in your own lab.

Snort 2 and Snort 3 have different configuration formats; adapt the include/configuration to your installed version.
