# QuadViewsCompanion
Quadviews Companion makes modifying the settings within mbucchia's implementation of QuadViews a breeze!

mbucchia's QuadViews is an essential download if you fly in VR, and you have eye-tracking enabled.

However, for many, the settings.cfg file setup and modification can prove difficult when trying to find the best Dynamic Foveated Rendering settings for DCS.

This handy utility not only automatically creates the initial QuadViews user settings file, but lets you load, modify, and update the settings without needing to open the config file at all.

See https://github.com/mbucchia/Quad-Views-Foveated/wiki for further details.

Works with Pimax Crystal, Pimax 12k, and Varjo Aero, Varjo XR3.

If needed: https://dotnet.microsoft.com/en-us/download/dotnet/6.0

Changelog v 1.0.11:
Updated to include application-based excludes introduced in QuadViews 1.1.3.

Changelog v 1.0.10:
Round error fixed - caused foveate region values greater than 200% not to be parsed from settings file correctly.

Changelog v 1.0.8-1.01:
Existing settings.cfg files that are of an incompatible format or may place some settings out of bounds, are renamed to "settings[date][time].cfg" in the same folder as the new format settings.cfg that is written - warning box alerts user to event
Modified to enforce replacement of comma decimals
Added link to this page (for updates)
Increased possible foveate SuperSampling amount to 300%
QV Defaults now read directly from original QuadViews default installation settings
Modified Presets
