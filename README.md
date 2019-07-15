# Sounds

> **Is this Interact Sound?** Sort of. This is the next iteration of Interact Sound with a redesigned API and the inclusion of directional audio.

## Introduction 

This resource provides directional audio services for FiveM sounds in-game to be created using standard audio
files, using a much cleaner API than previous iterations of this resource.

## Use Cases

Sounds is a resource that adds value in almost every use case where you need to play a custom sound, such as a seatbelt, beeps, alerts, tornado sirens, etc. The in-game mechanics of GTA V do not easily allow the streaming of extra audio files for scripts. As such, this resource aims to offer the ability for developers to get custom audio files playing in FiveM with the added benefit of also allowing the audio to be directional.

## Installation

Right now, the easiest way to install this resource is by downloading the zip file from the Releases and copying it into your `resources/` folder within FX Server.

## Contributing

I welcome contributions to this project, however, please note that the scope of this project has been set and pull requests that widen the scope will likely not be included without a good argument to do so. See the `CONTRIBUTING.md` file for more information on how to get started.

### The Scope

Time is something I don't have a lot of. With that being said, the scope of this project is set so that maintaining it does not take a lot of extra time. I'm happy to continue maintaining this resource and merging community contributions so long as scope creep doesn't occur with the pull requests. If the scope needs to be changed, there should be a solid reason for doing so. Happy to discuss this if the need arises!

 1. This resource SHOULD provide an easy way to register sounds so that the sound       files are tagged by name and are not accessed by the filename. The tags             should be namespaced on a per-resource basis. The ability to call the current       resource's namespace should be made possible without knowing the name of the        resource at the time of execution.

 2. This resource SHOULD provide an easy, expressive, and event-based API for           playing audio files either directionally or using standard mode where direction     and distance are not a factor (i.e., frontend sounds).

 3. This resource SHOULD be easily approachable by new users and should allow new       users to debug errors with the ability to enable verbose logging. The resource      should be able to be stopped and started at any time without the risk of the        resource not working for either existing or joining players.

 4. This resource SHOULD NOT set limits on the length of a sound file, the number of    files playing at a time, the number of registered files, or the number of           resources registering files at a time.

 5. This resource SHOULD overcome barriers related to the web audio API so that         specific files of certain lengths do not inhibit the resource's ease-of-use         requirement.
