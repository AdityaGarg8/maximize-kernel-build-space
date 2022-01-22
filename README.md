# Maximize available disk space for build tasks

If the available disk space on Github runners is too little for your build job, this action might be for you.
If not: please go on, there's nothing to see here.

This table shows the amount of free space you receive when using the action with the various options.

Android SDKs removed | .NET SDKs removed | Haskell removed | GB freed
--------------------:|:-----------------:|:---------------:|---------:
                     |                   |                 | 0
                     |                   | true            | Negligible
                     | true              |                 | 4
                     | true              | true            | almost 4
 true                |                   |                 | 15
 true                |                   | true            | almost 15
 true                | true              |                 | 19
 true                | true              | true            | almost 19
