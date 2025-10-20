## Usage

Place the following into Vencord's QuickCSS:

```less
@import url('https://abbie.github.io/discord-css/import.css');

:root {
	/* --------------------------------------- */
	/* configure changes this stylesheet makes */
	/* set ones you don't want active to false */
	/* --------------------------------------- */

	--\\--compact-title-bar: true;
	--\\--compact-input-box: true;
	--\\--compact-context-menu: true;
	--\\--compact-user-area: true;
	--\\--compact-channel-categories: true;
	--\\--compact-server-list: true;

	--\\--hide-nameplates: true;
	--\\--hide-guild-tags: true;
	--\\--hide-profile-effects: true;
	--\\--hide-avatar-decorations: false;
	--\\--hide-gradient-glow-usernames: true;
	--\\--hide-server-boost-goal: true;
	--\\--hide-server-activity: true;
	--\\--hide-user-activity: true;
	--\\--hide-context-menu-quick-reactions: true;
	--\\--hide-hover-quick-reactions: false;
	--\\--hide-image-edit-button: true;
	--\\--hide-gif-button: false;
	--\\--hide-sticker-button: false;
	--\\--hide-emoji-button: false;
	--\\--hide-apps-button: true;
	--\\--hide-gift-button: true;
	--\\--hide-help-button: false;
	--\\--hide-shop-button: false;
	--\\--hide-nitro-button: true;
	--\\--hide-quest-button: true;
	--\\--hide-active-now: true;
	--\\--hide-nitro-upsells: true;
	--\\--hide-vencord-desktop-platform-indicator: true;
	--\\--hide-cluttery-badges: false;
/* ^ hides quest, hypesquad, active dev, orb collector, and discriminator badges */

	--\\--darker-scrollbar: true;
	--\\--darker-hovered-message: true;
	--\\--prevent-sidebar-resizing: false;
	--\\--fix-minor-icon-misalignments: true;
}
```
