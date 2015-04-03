Until a write operation reaches a *majority* of replica set members, MongoDB may
roll it back during a single-node failure scenario. Use a *majority*
write concern to prevent this behavior.
