# Accessibility in CSS

## Reduced Motion

You can target users who are sensitive to animations and movement (and set up their system accordingly) with the prefers-reduced-motion media feature.

> @media (prefers-reduced-motion: reduce) {
> /_ CSS rules that are only applied when the user prefers reduced motion _/
> }

    💡 You can change your preferred reduced motion setting in your operating system settings. On macOS, you can do this in System Preferences > Accessibility > Display > Reduce motion.

## Inverted Colors

There are also media features for other (accessibility) features, like inverted-colors. The list of all media features is always growing. Check out the [full list on mdn](https://developer.mozilla.org/en-US/docs/Web/CSS/@media#media_features).
