BEFORE YOU START:
- you need Unity 2021.2+
- you need HD SRP pipline 12.1 or higer
- there is wind prefab which will manage wind at your scene
Be patient HD RP tech is so fluid... we coudn't fallow every beta version

Step 1 - Import our HD RP 12.1 Unity 2021.2 Mountain Tree Pack compatibility pack
Step 2 - Setup Shadows and other render setups.
- !!!! IMPORTANT !!!! Open "Project settings" ->"Gaphics"-> "HDRP global settings" ->  "Diffusion Profile Assets"
		  NM_SSSSettings_Skin_Foliage
		  NM_SSSSettings_Skin_NM Foliage
		  NM_SSSSettings_Skin_NM Foliage Trees
	Without this foliage materials will not become affected by scattering and they will look wrong.
	Open "HDRPMediumQuality" in project settings or "HDRPHighQuality" depends what unity use i your projectas default and:
	- Check if you got Deferred only in Lit Shader mode.
	- Check if contact shadows are turned on
	- LOD Bias to = 2 or 1.5
	- Check i you got screen space occlusion turned on
    - Check i you got screen space global ilumination turned on
	- Check i you got screen reflection and transparent turned on