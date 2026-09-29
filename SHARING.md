# Game release and sharing checklist

Start each new game or site in its own GitHub repository. Keep its source, assets, and deployment instructions there from the first build. Publish from that repository where practical, then connect its public URL to the appropriate hub, portfolio, or ministry site. Avoid bundling unrelated projects into one repository.\n\nEvery new Light & Life game should ship with its own distinct, readable 1200 × 630 preview image at `/og.png`. The image should carry the game title and recognizable artwork, with enough contrast to read in a small message preview. Use artwork that reflects the game's actual world and avoid presenting promotional key art as a gameplay screenshot.

In the game's `<head>` or framework metadata, set `og:type`, `og:title`, `og:description`, `og:url`, `og:image` (an absolute public URL), image width and height, and `twitter:card=summary_large_image` with matching title, description, and image. Keep the page title and description current.

Before announcing a release:

1. Confirm its dedicated GitHub repository contains the current source and the published URL points to this build.\n2. Publish the game and confirm the public `/og.png` loads without sign-in.
3. Check the live HTML has the intended Open Graph and X/Twitter metadata.
4. Add or update the game's card on this hub. Use the same finished artwork as the card image and link both the image and play button to the game.
5. Update the game count from the rendered cards and verify the hub on a narrow phone screen.
6. Update the Salt & Light Web Studio portfolio when the game belongs there.
7. Share the final URL in a chat to check title, description, and image; allow for messenger preview caching.

Treat preview artwork as a visual target for future game scenes, characters, menus, and effects. Keep controls and text readable for kids on phones.
