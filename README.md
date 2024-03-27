# TLDs
TLDs from https://data.iana.org/TLD/tlds-alpha-by-domain.txt for pihole use because I block everything DNS I don't need.

## This is a regex entry for pihole for all TLDs with some exclusions.

### The pihole TLD regex format is "(^|\.)(foo|bar)$"
#### Could I have used something shorter that needs less updating, - probs, but this is it for now
- continue to use blocklists as usual because any exclusions found here are TLDs and that's a bit nuts
- I don't dislike any particular TLD but some of these are just not useful to me and I never visit them
- this is a way for me to (from a DNS prespective), to manage a default-deny policy.
- Why is it on github
  - I thought I could just add a list and point pihole at this raw content, turns out, not so much.
  - This turned into a regex instead.
 
![image](https://github.com/jakesj425/TLD-pihole-regex/assets/13467643/3e563ec2-9582-4465-b602-262c687138a2)

