# Ease
Simple Unity3D Easing

	public enum EaseType
	{
		Linear,
		SineIn, SineOut, SineInOut,
		QuadIn, QuadOut, QuadInOut,
		CubicIn, CubicOut, CubicInOut,
		QuartIn, QuartOut, QuartInOut,
		QuintIn, QuintOut, QuintInOut,
		ExpoIn, ExpoOut, ExpoInOut,
		CircIn, CircOut, CircInOut,
		BackIn, BackOut, BackInOut,
		ElasticIn, ElasticOut, ElasticInOut,
		BounceIn, BounceOut, BounceInOut,
		Spring
	}

- Ease: ease a float, or alpha
	- Go
	- GoAlphaTo
	- GoAlphaBy
	- GoAlpha
- Ease3: ease a Vector2, or transform
	- Go
	- GoPositionTo
	- GoPositionBy
	- GoPosition
	- GoRotationTo
	- GoRotationBy
	- GoRotation
	- GoScaleTo
	- GoScaleBy
	- GoScale
- Ease4: ease a Vector4, or color
	- Go
	- GoColorTo
	- GoColorBy
	- GoColor
