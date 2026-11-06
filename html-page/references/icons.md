# Icons

141 icons from IconPark (Apache-2.0), the family the Seshat app itself uses: 48x48 grid, 4px round stroke, colour taken from the text colour (`currentColor`). Find one with grep on its name (`### Name`), copy its `<svg>` into the page and give it the `icon` class.

```css
.icon{width:20px;height:20px;flex:none}
```

```html
<span class="icon-row"><svg class="icon" viewBox="0 0 48 48" ...>...</svg> Label</span>
```

Names are grouped: Actions, Arrows, Files and data, Tech, People and places. If the icon you need is not here, draw a simple one yourself in the same style (stroke 4 on a 48 grid, round caps, no fill) rather than using an emoji.

## Actions

### Plus
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24.0605 10L24.0239 38" stroke="currentColor" stroke-width="4"/><path d="M10 24L38 24" stroke="currentColor" stroke-width="4"/></svg>

### Minus
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M10.5 24L38.5 24" stroke="currentColor" stroke-width="4"/></svg>

### Close
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M8 8L40 40" stroke="currentColor" stroke-width="4"/><path d="M8 40L40 8" stroke="currentColor" stroke-width="4"/></svg>

### CloseOne
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 44C35.0457 44 44 35.0457 44 24C44 12.9543 35.0457 4 24 4C12.9543 4 4 12.9543 4 24C4 35.0457 12.9543 44 24 44Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M29.6567 18.3432L18.343 29.6569" stroke="currentColor" stroke-width="4"/><path d="M18.3433 18.3432L29.657 29.6569" stroke="currentColor" stroke-width="4"/></svg>

### Check
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M43 11L16.875 37L5 25.1818" stroke="currentColor" stroke-width="4"/></svg>

### CheckOne
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 44C29.5228 44 34.5228 41.7614 38.1421 38.1421C41.7614 34.5228 44 29.5228 44 24C44 18.4772 41.7614 13.4772 38.1421 9.85786C34.5228 6.23858 29.5228 4 24 4C18.4772 4 13.4772 6.23858 9.85786 9.85786C6.23858 13.4772 4 18.4772 4 24C4 29.5228 6.23858 34.5228 9.85786 38.1421C13.4772 41.7614 18.4772 44 24 44Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M16 24L22 30L34 18" stroke="currentColor" stroke-width="4"/></svg>

### Edit
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M7 42H43" stroke="currentColor" stroke-width="4"/><path d="M11 26.7199V34H18.3172L39 13.3081L31.6951 6L11 26.7199Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Delete
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M9 10V44H39V10H9Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M20 20V33" stroke="currentColor" stroke-width="4"/><path d="M28 20V33" stroke="currentColor" stroke-width="4"/><path d="M4 10H44" stroke="currentColor" stroke-width="4"/><path d="M16 10L19.289 4H28.7771L32 10H16Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Copy
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M13 12.4316V7.8125C13 6.2592 14.2592 5 15.8125 5H40.1875C41.7408 5 43 6.2592 43 7.8125V32.1875C43 33.7408 41.7408 35 40.1875 35H35.5163" stroke="currentColor" stroke-width="4"/><path d="M32.1875 13H7.8125C6.2592 13 5 14.2592 5 15.8125V40.1875C5 41.7408 6.2592 43 7.8125 43H32.1875C33.7408 43 35 41.7408 35 40.1875V15.8125C35 14.2592 33.7408 13 32.1875 13Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Download
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M6 24.0083V42H42V24" stroke="currentColor" stroke-width="4"/><path d="M33 23L24 32L15 23" stroke="currentColor" stroke-width="4"/><path d="M23.9917 6V32" stroke="currentColor" stroke-width="4"/></svg>

### Upload
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><mask id="icon-4fa3618c7070702c" maskUnits="userSpaceOnUse" x="0" y="0" width="48" height="48" style="mask-type:alpha"><path d="M48 0H0V48H48V0Z" fill="currentColor"/></mask><g mask="url(#icon-4fa3618c7070702c)"><path d="M6 24.0083V42H42V24" stroke="currentColor" stroke-width="4"/><path d="M33 15L24 6L15 15" stroke="currentColor" stroke-width="4"/><path d="M23.9917 32V6" stroke="currentColor" stroke-width="4"/></g></svg>

### Share
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M28 6H42V20" stroke="currentColor" stroke-width="4"/><path d="M42 29.4737V39C42 40.6569 40.6569 42 39 42H9C7.34315 42 6 40.6569 6 39V9C6 7.34315 7.34315 6 9 6L18 6" stroke="currentColor" stroke-width="4"/><path d="M25.7998 22.1999L41.0998 6.8999" stroke="currentColor" stroke-width="4"/></svg>

### ShareOne
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M35 16C37.7614 16 40 13.7614 40 11C40 8.23858 37.7614 6 35 6C32.2386 6 30 8.23858 30 11C30 13.7614 32.2386 16 35 16Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M13 29C15.7614 29 18 26.7614 18 24C18 21.2386 15.7614 19 13 19C10.2386 19 8 21.2386 8 24C8 26.7614 10.2386 29 13 29Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M30.0004 13.5745L17.3393 21.2454" stroke="currentColor" stroke-width="4"/><path d="M17.3385 26.5639L30.6789 34.4469" stroke="currentColor" stroke-width="4"/><path d="M35 32C37.7614 32 40 34.2386 40 37C40 39.7614 37.7614 42 35 42C32.2386 42 30 39.7614 30 37C30 34.2386 32.2386 32 35 32Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Refresh
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M42 8V24" stroke="currentColor" stroke-width="4"/><path d="M6 24L6 40" stroke="currentColor" stroke-width="4"/><path d="M42 24C42 14.0589 33.9411 6 24 6C18.9145 6 14.3216 8.10896 11.0481 11.5M6 24C6 33.9411 14.0589 42 24 42C28.8556 42 33.2622 40.0774 36.5 36.9519" stroke="currentColor" stroke-width="4"/></svg>

### Search
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M21 38C30.3888 38 38 30.3888 38 21C38 11.6112 30.3888 4 21 4C11.6112 4 4 11.6112 4 21C4 30.3888 11.6112 38 21 38Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M26.657 14.3431C25.2093 12.8954 23.2093 12 21.0001 12C18.791 12 16.791 12.8954 15.3433 14.3431" stroke="currentColor" stroke-width="4"/><path d="M33.2216 33.2217L41.7069 41.707" stroke="currentColor" stroke-width="4"/></svg>

### Filter
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M6 9L20.4 25.8178V38.4444L27.6 42V25.8178L42 9H6Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### SortThree
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M25 14L16 5L7 14" stroke="currentColor" stroke-width="4"/><path d="M15.9917 31V5" stroke="currentColor" stroke-width="4"/><path d="M42 34L33 43L24 34" stroke="currentColor" stroke-width="4"/><path d="M32.9917 17V43" stroke="currentColor" stroke-width="4"/></svg>

### More
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="24" r="3" fill="currentColor"/><circle cx="24" cy="24" r="3" fill="currentColor"/><circle cx="36" cy="24" r="3" fill="currentColor"/></svg>

### SettingTwo
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M18.2838 43.1713C14.9327 42.1736 11.9498 40.3213 9.58787 37.867C10.469 36.8227 11 35.4734 11 34.0001C11 30.6864 8.31371 28.0001 5 28.0001C4.79955 28.0001 4.60139 28.01 4.40599 28.0292C4.13979 26.7277 4 25.3803 4 24.0001C4 21.9095 4.32077 19.8938 4.91579 17.9995C4.94381 17.9999 4.97188 18.0001 5 18.0001C8.31371 18.0001 11 15.3138 11 12.0001C11 11.0488 10.7786 10.1493 10.3846 9.35011C12.6975 7.1995 15.5205 5.59002 18.6521 4.72314C19.6444 6.66819 21.6667 8.00013 24 8.00013C26.3333 8.00013 28.3556 6.66819 29.3479 4.72314C32.4795 5.59002 35.3025 7.1995 37.6154 9.35011C37.2214 10.1493 37 11.0488 37 12.0001C37 15.3138 39.6863 18.0001 43 18.0001C43.0281 18.0001 43.0562 17.9999 43.0842 17.9995C43.6792 19.8938 44 21.9095 44 24.0001C44 25.3803 43.8602 26.7277 43.594 28.0292C43.3986 28.01 43.2005 28.0001 43 28.0001C39.6863 28.0001 37 30.6864 37 34.0001C37 35.4734 37.531 36.8227 38.4121 37.867C36.0502 40.3213 33.0673 42.1736 29.7162 43.1713C28.9428 40.752 26.676 39.0001 24 39.0001C21.324 39.0001 19.0572 40.752 18.2838 43.1713Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M24 31C27.866 31 31 27.866 31 24C31 20.134 27.866 17 24 17C20.134 17 17 20.134 17 24C17 27.866 20.134 31 24 31Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Save
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M6 9C6 7.34315 7.34315 6 9 6H34.2814L42 13.2065V39C42 40.6569 40.6569 42 39 42H9C7.34315 42 6 40.6569 6 39V9Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path fill-rule="evenodd" clip-rule="evenodd" d="M24.0083 6L24 13.3846C24 13.7245 23.5523 14 23 14H15C14.4477 14 14 13.7245 14 13.3846L14 6" fill="none"/><path d="M24.0083 6L24 13.3846C24 13.7245 23.5523 14 23 14H15C14.4477 14 14 13.7245 14 13.3846L14 6H24.0083Z" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M9 6H34.2814" stroke="currentColor" stroke-width="4"/><path d="M14 26H34" stroke="currentColor" stroke-width="4"/><path d="M14 34H24.0083" stroke="currentColor" stroke-width="4"/></svg>

### LinkOne
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M26.2401 16.373L17.1001 7.23303C14.4388 4.57168 10.0653 4.6303 7.33158 7.36397C4.59791 10.0976 4.53929 14.4712 7.20064 17.1325L15.1359 25.0678" stroke="currentColor" stroke-width="4"/><path d="M32.9027 23.0031L40.838 30.9384C43.4994 33.5998 43.4407 37.9733 40.7071 40.707C37.9734 43.4407 33.5999 43.4993 30.9385 40.8379L21.7985 31.6979" stroke="currentColor" stroke-width="4"/><path d="M26.1093 26.1416C28.843 23.4079 28.9016 19.0344 26.2403 16.373" stroke="currentColor" stroke-width="4"/><path d="M21.7989 21.7984C19.0652 24.5321 19.0066 28.9056 21.6679 31.5669" stroke="currentColor" stroke-width="4"/></svg>

### Printer
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M37 32H11V44H37V32Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path fill-rule="evenodd" clip-rule="evenodd" d="M4 20H44V38H37.0173V32H10.9805V38H4V20Z" stroke="currentColor" stroke-width="4"/><path d="M38 4H10V20H38V4Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Lock
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><rect x="6" y="22" width="36" height="22" rx="2" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M14 22V14C14 8.47715 18.4772 4 24 4C29.5228 4 34 8.47715 34 14V22" stroke="currentColor" stroke-width="4"/><path d="M24 30V36" stroke="currentColor" stroke-width="4"/></svg>

### Unlock
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><rect x="7" y="22.0476" width="34" height="22" rx="2" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M14 22V14.0047C13.9948 8.87022 17.9227 4.56718 23.0859 4.05117C28.249 3.53516 32.9673 6.97408 34 12.0059" stroke="currentColor" stroke-width="4"/><path d="M24 30V36" stroke="currentColor" stroke-width="4"/></svg>

### Star
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M23.9986 5L17.8856 17.4776L4 19.4911L14.0589 29.3251L11.6544 43L23.9986 36.4192L36.3454 43L33.9586 29.3251L44 19.4911L30.1913 17.4776L23.9986 5Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Like
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M15 8C8.92487 8 4 12.9249 4 19C4 30 17 40 24 42.3262C31 40 44 30 44 19C44 12.9249 39.0751 8 33 8C29.2797 8 25.9907 9.8469 24 12.6738C22.0093 9.8469 18.7203 8 15 8Z" fill="none" stroke="currentColor" stroke-width="4"/></svg>

### Mail
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M4 39H44V24V9H24H4V24V39Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M4 9L24 24L44 9" stroke="currentColor" stroke-width="4"/><path d="M24 9H4V24" stroke="currentColor" stroke-width="4"/><path d="M44 24V9H24" stroke="currentColor" stroke-width="4"/></svg>

### SendEmail
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M44 24V9H24H4V24V39H24" stroke="currentColor" stroke-width="4"/><path d="M44 34L30 34" stroke="currentColor" stroke-width="4"/><path d="M39 29L44 34L39 39" stroke="currentColor" stroke-width="4"/><path d="M4 9L24 24L44 9" stroke="currentColor" stroke-width="4"/></svg>

### Attention
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 44C29.5228 44 34.5228 41.7614 38.1421 38.1421C41.7614 34.5228 44 29.5228 44 24C44 18.4772 41.7614 13.4772 38.1421 9.85786C34.5228 6.23858 29.5228 4 24 4C18.4772 4 13.4772 6.23858 9.85786 9.85786C6.23858 13.4772 4 18.4772 4 24C4 29.5228 6.23858 34.5228 9.85786 38.1421C13.4772 41.7614 18.4772 44 24 44Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path fill-rule="evenodd" clip-rule="evenodd" d="M24 37C25.3807 37 26.5 35.8807 26.5 34.5C26.5 33.1193 25.3807 32 24 32C22.6193 32 21.5 33.1193 21.5 34.5C21.5 35.8807 22.6193 37 24 37Z" fill="currentColor"/><path d="M24 12V28" stroke="currentColor" stroke-width="4"/></svg>

### Help
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 44C29.5228 44 34.5228 41.7614 38.1421 38.1421C41.7614 34.5228 44 29.5228 44 24C44 18.4772 41.7614 13.4772 38.1421 9.85786C34.5228 6.23858 29.5228 4 24 4C18.4772 4 13.4772 6.23858 9.85786 9.85786C6.23858 13.4772 4 18.4772 4 24C4 29.5228 6.23858 34.5228 9.85786 38.1421C13.4772 41.7614 18.4772 44 24 44Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M24 28.6248V24.6248C27.3137 24.6248 30 21.9385 30 18.6248C30 15.3111 27.3137 12.6248 24 12.6248C20.6863 12.6248 18 15.3111 18 18.6248" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M24 37.6248C25.3807 37.6248 26.5 36.5055 26.5 35.1248C26.5 33.7441 25.3807 32.6248 24 32.6248C22.6193 32.6248 21.5 33.7441 21.5 35.1248C21.5 36.5055 22.6193 37.6248 24 37.6248Z" fill="currentColor"/></svg>

### Info
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 44C29.5228 44 34.5228 41.7614 38.1421 38.1421C41.7614 34.5228 44 29.5228 44 24C44 18.4772 41.7614 13.4772 38.1421 9.85786C34.5228 6.23858 29.5228 4 24 4C18.4772 4 13.4772 6.23858 9.85786 9.85786C6.23858 13.4772 4 18.4772 4 24C4 29.5228 6.23858 34.5228 9.85786 38.1421C13.4772 41.7614 18.4772 44 24 44Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path fill-rule="evenodd" clip-rule="evenodd" d="M24 11C25.3807 11 26.5 12.1193 26.5 13.5C26.5 14.8807 25.3807 16 24 16C22.6193 16 21.5 14.8807 21.5 13.5C21.5 12.1193 22.6193 11 24 11Z" fill="currentColor"/><path d="M24.5 34V20H23.5H22.5" stroke="currentColor" stroke-width="4"/><path d="M21 34H28" stroke="currentColor" stroke-width="4"/></svg>

### Caution
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path fill-rule="evenodd" clip-rule="evenodd" d="M24 5L2 43H46L24 5Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M24 35V36" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M24 19.0005L24.0083 29" stroke="currentColor" stroke-width="4" stroke-linecap="round"/></svg>

### Power
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M14.5 8C13.8406 8.37652 13.2062 8.79103 12.6 9.24051C11.5625 10.0097 10.6074 10.8814 9.75 11.8402C6.79377 15.1463 5 19.4891 5 24.2455C5 34.6033 13.5066 43 24 43C34.4934 43 43 34.6033 43 24.2455C43 19.4891 41.2062 15.1463 38.25 11.8402C37.3926 10.8814 36.4375 10.0097 35.4 9.24051C34.7938 8.79103 34.1594 8.37652 33.5 8" stroke="currentColor" stroke-width="4"/><path d="M24 4V24" stroke="currentColor" stroke-width="4"/></svg>

## Arrows

### Up
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M13 30L25 18L37 30" stroke="currentColor" stroke-width="4"/></svg>

### Down
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M36 18L24 30L12 18" stroke="currentColor" stroke-width="4"/></svg>

### Left
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M31 36L19 24L31 12" stroke="currentColor" stroke-width="4"/></svg>

### Right
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M19 12L31 24L19 36" stroke="currentColor" stroke-width="4"/></svg>

### ArrowUp
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 6V42" stroke="currentColor" stroke-width="4"/><path d="M12 18L24 6L36 18" stroke="currentColor" stroke-width="4"/></svg>

### ArrowDown
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 42V6" stroke="currentColor" stroke-width="4"/><path d="M36 30L24 42L12 30" stroke="currentColor" stroke-width="4"/></svg>

### ArrowLeft
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M5.79889 24H41.7989" stroke="currentColor" stroke-width="4"/><path d="M17.7988 36L5.79883 24L17.7988 12" stroke="currentColor" stroke-width="4"/></svg>

### ArrowRight
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M41.9999 24H5.99994" stroke="currentColor" stroke-width="4"/><path d="M30 12L42 24L30 36" stroke="currentColor" stroke-width="4"/></svg>

### DoubleRight
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M12 12L24 24L12 36" stroke="currentColor" stroke-width="4"/><path d="M24 12L36 24L24 36" stroke="currentColor" stroke-width="4"/></svg>

### DoubleLeft
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 36L12 24L24 12" stroke="currentColor" stroke-width="4"/><path d="M36 36L24 24L36 12" stroke="currentColor" stroke-width="4"/></svg>

### Back
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path fill-rule="evenodd" clip-rule="evenodd" d="M44 40.8361C39.1069 34.8632 34.7617 31.4739 30.9644 30.6682C27.1671 29.8625 23.5517 29.7408 20.1182 30.303V41L4 23.5453L20.1182 7V17.167C26.4667 17.2172 31.8638 19.4948 36.3095 24C40.7553 28.5052 43.3187 34.1172 44 40.8361Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Return
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M12.9998 8L6 14L12.9998 21" stroke="currentColor" stroke-width="4"/><path d="M6 14H28.9938C35.8768 14 41.7221 19.6204 41.9904 26.5C42.2739 33.7696 36.2671 40 28.9938 40H11.9984" stroke="currentColor" stroke-width="4"/></svg>

### Switch
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M42 19H5.99998" stroke="currentColor" stroke-width="4"/><path d="M30 7L42 19" stroke="currentColor" stroke-width="4"/><path d="M6.79897 29H42.799" stroke="currentColor" stroke-width="4"/><path d="M6.79895 29L18.799 41" stroke="currentColor" stroke-width="4"/></svg>

### Transfer
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M37 28.3923V35.4066C37 39.048 34.0885 42 30.497 42C26.9054 42 23.9939 39.048 23.9939 35.4066L24.0061 13.1429C24.0061 9.19797 21.0946 6 17.503 6C13.9115 6 11 9.19797 11 13.1429V28.3923" stroke="currentColor" stroke-width="4"/><path d="M43 31L37 25L31 31" stroke="currentColor" stroke-width="4"/><path d="M43 10.7273C43 15.1818 37 19 37 19C37 19 31 15.1818 31 10.7273C31 9.20831 31.6321 7.75155 32.7574 6.67748C33.8826 5.60341 35.4087 5 37 5C38.5913 5 40.1174 5.60341 41.2426 6.67748C42.3679 7.75155 43 9.20831 43 10.7273Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M17 34.7273C17 39.1818 11 43 11 43C11 43 5 39.1818 5 34.7273C5 33.2083 5.63214 31.7516 6.75736 30.6775C7.88258 29.6034 9.4087 29 11 29C12.5913 29 14.1174 29.6034 15.2426 30.6775C16.3679 31.7516 17 33.2083 17 34.7273Z" fill="none" stroke="currentColor" stroke-width="4"/><circle cx="37" cy="11" r="2" fill="currentColor"/><circle cx="11" cy="35" r="2" fill="currentColor"/></svg>

### FullScreen
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M33 6H42V15" stroke="currentColor" stroke-width="4"/><path d="M42 33V42H33" stroke="currentColor" stroke-width="4"/><path d="M15 42H6V33" stroke="currentColor" stroke-width="4"/><path d="M6 15V6H15" stroke="currentColor" stroke-width="4"/></svg>

### Rotate
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M12 24H42V42H12V24Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M6 8V17H15" stroke="currentColor" stroke-width="4"/><path d="M38.4747 13.2985C35.1956 8.87049 29.933 6 24 6C18.1788 6 13.0029 8.76334 9.71272 13.0498L6 17" stroke="currentColor" stroke-width="4"/></svg>

### Redo
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M36.7279 36.7279C33.4706 39.9853 28.9706 42 24 42C14.0589 42 6 33.9411 6 24C6 14.0589 14.0589 6 24 6C28.9706 6 33.4706 8.01472 36.7279 11.2721C38.3859 12.9301 42 17 42 17" stroke="currentColor" stroke-width="4"/><path d="M42 8V17H33" stroke="currentColor" stroke-width="4"/></svg>

### Undo
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M11.2721 36.7279C14.5294 39.9853 19.0294 42 24 42C33.9411 42 42 33.9411 42 24C42 14.0589 33.9411 6 24 6C19.0294 6 14.5294 8.01472 11.2721 11.2721C9.61407 12.9301 6 17 6 17" stroke="currentColor" stroke-width="4"/><path d="M6 9V17H14" stroke="currentColor" stroke-width="4"/></svg>

### LoadingOne
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 4V8" stroke="currentColor" stroke-width="4"/><path d="M34 6.6795L32 10.1436" stroke="currentColor" stroke-width="4"/><path d="M41.3203 14L37.8562 16" stroke="currentColor" stroke-width="4"/><path d="M44 24H40" stroke="currentColor" stroke-width="4"/><path d="M41.3203 34L37.8562 32" stroke="currentColor" stroke-width="4"/><path d="M34 41.3205L32 37.8564" stroke="currentColor" stroke-width="4"/><path d="M24 44V40" stroke="currentColor" stroke-width="4"/><path d="M14 41.3205L16 37.8564" stroke="currentColor" stroke-width="4"/><path d="M6.67969 34L10.1438 32" stroke="currentColor" stroke-width="4"/><path d="M4 24H8" stroke="currentColor" stroke-width="4"/><path d="M6.67969 14L10.1438 16" stroke="currentColor" stroke-width="4"/><path d="M14 6.6795L16 10.1436" stroke="currentColor" stroke-width="4"/></svg>

### TrendTwo
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M4 44H44" stroke="currentColor" stroke-width="4"/><path d="M4 26L12 28V38H4V26Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M20 24L28 20V38H20V24Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M36 16L44 12V38H36V16Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M4 18L12 20L44 4H34" stroke="currentColor" stroke-width="4"/></svg>

### Trend
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M39 6H9C7.34315 6 6 7.34315 6 9V39C6 40.6569 7.34315 42 9 42H39C40.6569 42 42 40.6569 42 39V9C42 7.34315 40.6569 6 39 6Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M13.4398 29.8347L19.0967 24.1778L23.4847 28.5555L34 18.0001" stroke="currentColor" stroke-width="4"/><path d="M26 18H34V26" stroke="currentColor" stroke-width="4"/></svg>

## Files and data

### FileText
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M10 44H38C39.1046 44 40 43.1046 40 42V14H30V4H10C8.89543 4 8 4.89543 8 6V42C8 43.1046 8.89543 44 10 44Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M30 4L40 14" stroke="currentColor" stroke-width="4"/><path d="M24 22V36" stroke="currentColor" stroke-width="4"/><path d="M18 22H24L30 22" stroke="currentColor" stroke-width="4"/></svg>

### FileTextOne
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M40 23V14L31 4H10C8.89543 4 8 4.89543 8 6V42C8 43.1046 8.89543 44 10 44H22" stroke="currentColor" stroke-width="4"/><path d="M34 30V44" stroke="currentColor" stroke-width="4"/><path d="M28 30H34L40 30" stroke="currentColor" stroke-width="4"/><path d="M30 4V14H40" stroke="currentColor" stroke-width="4"/></svg>

### FileCode
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M10 44H38C39.1046 44 40 43.1046 40 42V14H30V4H10C8.89543 4 8 4.89543 8 6V42C8 43.1046 8.89543 44 10 44Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M30 4L40 14" stroke="currentColor" stroke-width="4"/><path d="M27 24L32 29L27 34" stroke="currentColor" stroke-width="4"/><path d="M21 24L16 29L21 34" stroke="currentColor" stroke-width="4"/></svg>

### FileDoc
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M10 38V44H38V38" stroke="currentColor" stroke-width="4"/><path d="M38 20V14L30 4H10V20" stroke="currentColor" stroke-width="4"/><path d="M28 4V14H38" stroke="currentColor" stroke-width="4"/><path d="M16 12H20" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><rect x="4" y="20" width="40" height="18" rx="2" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M10 25V33" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M10 25H12C14.2091 25 16 26.7909 16 29V29C16 31.2091 14.2091 33 12 33H10" stroke="currentColor" stroke-width="4"/><ellipse cx="24" cy="29" rx="3" ry="4" stroke="currentColor" stroke-width="4"/><path d="M38 25H36C33.7909 25 32 26.7909 32 29V29C32 31.2091 33.7909 33 36 33H38" stroke="currentColor" stroke-width="4"/></svg>

### FileZip
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M10 38V44H38V38" stroke="currentColor" stroke-width="4"/><path d="M38 20V14L30 4H10V20" stroke="currentColor" stroke-width="4"/><path d="M28 4V14H38" stroke="currentColor" stroke-width="4"/><path d="M16 12H20" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><rect x="4" y="20" width="40" height="18" rx="2" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M11 25H17L11 33H17" stroke="currentColor" stroke-width="4"/><path d="M24 25V33" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M31 25V33" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M31 25H34.5C35.8807 25 37 26.1193 37 27.5V27.5C37 28.8807 35.8807 30 34.5 30H31" stroke="currentColor" stroke-width="4"/></svg>

### Folder
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M7 6C7 4.89543 7.89543 4 9 4H39C40.1046 4 41 4.89543 41 6V42C41 43.1046 40.1046 44 39 44H9C7.89543 44 7 43.1046 7 42V6Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M16 29H20" stroke="currentColor" stroke-width="4"/><path d="M16 35H26" stroke="currentColor" stroke-width="4"/><path d="M8 5C8 5 11.7647 18 24 18C36.2353 18 40 5 40 5" stroke="currentColor" stroke-width="4"/><circle cx="24" cy="18" r="4" fill="none" stroke="currentColor" stroke-width="4"/><path d="M15 4H9C7.89543 4 7 4.89543 7 6V12" stroke="currentColor" stroke-width="4"/><path d="M33 4H39C40.1046 4 41 4.89543 41 6V12" stroke="currentColor" stroke-width="4"/></svg>

### FolderOpen
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M4 9V41L9 21H39.5V15C39.5 13.8954 38.6046 13 37.5 13H24L19 7H6C4.89543 7 4 7.89543 4 9Z" stroke="currentColor" stroke-width="4"/><path d="M40 41L44 21H8.8125L4 41H40Z" fill="none" stroke="currentColor" stroke-width="4"/></svg>

### DataSheet
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><rect x="4" y="8" width="40" height="32" rx="2" fill="none" stroke="currentColor" stroke-width="4"/><path d="M32 25V32" stroke="currentColor" stroke-width="4"/><path d="M24 16V32" stroke="currentColor" stroke-width="4"/><path d="M16 20V32" stroke="currentColor" stroke-width="4"/></svg>

### Table
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><rect x="8" y="4" width="32" height="40" rx="2" fill="none" stroke="currentColor" stroke-width="4"/><path d="M14 16H34" stroke="currentColor" stroke-width="4"/><path d="M14 24H34" stroke="currentColor" stroke-width="4"/><path d="M14 32H34" stroke="currentColor" stroke-width="4"/><path d="M18 12V36" stroke="currentColor" stroke-width="4"/></svg>

### ChartHistogram
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M6 6V42H42" stroke="currentColor" stroke-width="4"/><path d="M14 30V34" stroke="currentColor" stroke-width="4"/><path d="M22 22V34" stroke="currentColor" stroke-width="4"/><path d="M30 6V34" stroke="currentColor" stroke-width="4"/><path d="M38 14V34" stroke="currentColor" stroke-width="4"/></svg>

### ChartLine
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M6 6V42H42" stroke="currentColor" stroke-width="4"/><path d="M14 34L22 18L32 27L42 6" stroke="currentColor" stroke-width="4"/></svg>

### ChartPie
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M44 24C44 35.0457 35.0457 44 24 44C12.9543 44 4 35.0457 4 24C4 12.9543 12.9543 4 24 4V24H44Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M43.0844 18H30V4.91553C36.2202 6.86917 41.1308 11.7798 43.0844 18Z" fill="none" stroke="currentColor" stroke-width="4"/></svg>

### ChartGraph
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><rect x="17" y="6" width="14" height="9" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><rect x="6" y="33" width="14" height="9" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><rect x="28" y="33" width="14" height="9" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M24 16V24" stroke="currentColor" stroke-width="4"/><path d="M13 33V24H35V33" stroke="currentColor" stroke-width="4"/></svg>

### ChartProportion
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M16.3446 5.51758C13.9 6.53124 11.7001 8.01574 9.85786 9.85797C6.23858 13.4773 4 18.4773 4 24.0001C4 35.0458 12.9543 44.0001 24 44.0001V44.0001C29.5228 44.0001 34.5228 41.7615 38.1421 38.1422C39.9844 36.3 41.4689 34.1001 42.4825 31.6555" stroke="currentColor" stroke-width="4"/><path d="M24 24H44C44 12.9543 35.0457 4 24 4L24 24Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Analysis
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M44 5H3.99998V17H44V5Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M3.99998 41.0301L16.1756 28.7293L22.7549 35.0301L30.7982 27L35.2786 31.368" stroke="currentColor" stroke-width="4"/><path d="M44 16.1719V42.1719" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M3.99998 16.1719V30.1719" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M13.0155 43H44" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M17 11H38" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M9.99998 10.9966H11" stroke="currentColor" stroke-width="4" stroke-linecap="round"/></svg>

### Calendar
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M5 19H43V40C43 41.1046 42.1046 42 41 42H7C5.89543 42 5 41.1046 5 40V19Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M5 9C5 7.89543 5.89543 7 7 7H41C42.1046 7 43 7.89543 43 9V19H5V9Z" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M16 4V12" stroke="currentColor" stroke-width="4"/><path d="M32 4V12" stroke="currentColor" stroke-width="4"/><path d="M28 34H34" stroke="currentColor" stroke-width="4"/><path d="M14 34H20" stroke="currentColor" stroke-width="4"/><path d="M28 26H34" stroke="currentColor" stroke-width="4"/><path d="M14 26H20" stroke="currentColor" stroke-width="4"/></svg>

### Time
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 44C35.0457 44 44 35.0457 44 24C44 12.9543 35.0457 4 24 4C12.9543 4 4 12.9543 4 24C4 35.0457 12.9543 44 24 44Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M24.0084 12.0001L24.0072 24.0089L32.4866 32.4883" stroke="currentColor" stroke-width="4"/></svg>

### Timer
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><circle cx="24" cy="28" r="16" fill="none" stroke="currentColor" stroke-width="4"/><path d="M28 4L20 4" stroke="currentColor" stroke-width="4"/><path d="M24 4V12" stroke="currentColor" stroke-width="4"/><path d="M35 16L38 13" stroke="currentColor" stroke-width="4"/><path d="M24 28V22" stroke="currentColor" stroke-width="4"/><path d="M24 28H18" stroke="currentColor" stroke-width="4"/></svg>

### History
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M5.81836 6.72729V14H13.0911" stroke="currentColor" stroke-width="4"/><path d="M4 24C4 35.0457 12.9543 44 24 44V44C35.0457 44 44 35.0457 44 24C44 12.9543 35.0457 4 24 4C16.598 4 10.1351 8.02111 6.67677 13.9981" stroke="currentColor" stroke-width="4"/><path d="M24.005 12L24.0038 24.0088L32.4832 32.4882" stroke="currentColor" stroke-width="4"/></svg>

### Bookmark
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M10 44C8.89543 44 8 43.1046 8 42V6C8 4.89543 8.89543 4 10 4H38C39.1046 4 40 4.89543 40 6V42C40 43.1046 39.1046 44 38 44H10Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path fill-rule="evenodd" clip-rule="evenodd" d="M21 22V4H33V22L27 15.7273L21 22Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M10 4H38" stroke="currentColor" stroke-width="4"/></svg>

### Tag
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M8 44L8 6C8 4.89543 8.89543 4 10 4H38C39.1046 4 40 4.89543 40 6V44L24 35.7273L8 44Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M16 18H32" stroke="currentColor" stroke-width="4"/></svg>

### Notebook
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M10 6C10 4.89543 10.8954 4 12 4H40C41.1046 4 42 4.89543 42 6V42C42 43.1046 41.1046 44 40 44H12C10.8954 44 10 43.1046 10 42V6Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M34 6V42" stroke="currentColor" stroke-width="4"/><path d="M6 14H14" stroke="currentColor" stroke-width="4"/><path d="M6 24H14" stroke="currentColor" stroke-width="4"/><path d="M6 34H14" stroke="currentColor" stroke-width="4"/><path d="M27 4H39" stroke="currentColor" stroke-width="4"/><path d="M27 44H39" stroke="currentColor" stroke-width="4"/></svg>

### Paperclip
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M26.1219 37.4352C26.1219 37.4352 37.4356 26.1215 40.264 23.293C43.0924 20.4646 44.5066 13.3935 39.5569 8.4438C34.6071 3.49405 27.5361 4.90826 24.7076 7.73669C21.8792 10.5651 7.02998 25.4144 5.61576 26.8286C4.20155 28.2428 2.08023 33.1925 6.32287 37.4352C10.5655 41.6778 15.5153 39.5565 16.9295 38.1423C18.3437 36.7281 33.9 21.1717 35.3142 19.7575C36.7285 18.3433 37.4356 14.8078 35.3142 12.6864C33.1929 10.5651 29.6574 11.2722 28.2432 12.6864C26.829 14.1007 14.8082 26.1215 14.8082 26.1215" stroke="currentColor" stroke-width="4"/></svg>

## Tech

### Code
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M16 13L4 25.4322L16 37" stroke="currentColor" stroke-width="4"/><path d="M32 13L44 25.4322L32 37" stroke="currentColor" stroke-width="4"/><path d="M28 4L21 44" stroke="currentColor" stroke-width="4" stroke-linecap="round"/></svg>

### CodeBrackets
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M16 4C14 4 11 5 11 9C11 13 11 15 11 18C11 21 6 23 6 23C6 23 11 25 11 28C11 31 11 35 11 39C11 43 14 44 16 44" stroke="currentColor" stroke-width="4"/><path d="M32 4C34 4 37 5 37 9C37 13 37 15 37 18C37 21 42 23 42 23C42 23 37 25 37 28C37 31 37 35 37 39C37 43 34 44 32 44" stroke="currentColor" stroke-width="4"/></svg>

### Terminal
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><rect x="4" y="8" width="40" height="32" rx="2" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M12 18L19 24L12 30" stroke="currentColor" stroke-width="4"/><path d="M23 32H36" stroke="currentColor" stroke-width="4"/></svg>

### Computer
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><rect x="19" y="32" width="10" height="9" stroke="currentColor" stroke-width="4"/><rect x="5" y="8" width="38" height="24" rx="2" fill="none" stroke="currentColor" stroke-width="4"/><path d="M22 27H26" stroke="currentColor" stroke-width="4"/><path d="M14 41L34 41" stroke="currentColor" stroke-width="4"/></svg>

### Cpu
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M38 8H10C8.89543 8 8 8.89543 8 10V38C8 39.1046 8.89543 40 10 40H38C39.1046 40 40 39.1046 40 38V10C40 8.89543 39.1046 8 38 8Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M30 18H18V30H30V18Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path fill-rule="evenodd" clip-rule="evenodd" d="M14.9092 2V8V2Z" fill="none"/><path d="M14.9092 2V8" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M14.9092 40V46V40Z" fill="none"/><path d="M14.9092 40V46" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M24 2V8V2Z" fill="none"/><path d="M24 2V8" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M24 40V46V40Z" fill="none"/><path d="M24 40V46" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M33.0908 2V8V2Z" fill="none"/><path d="M33.0908 2V8" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M33.0908 40V46V40Z" fill="none"/><path d="M33.0908 40V46" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M2 14.9092H8H2Z" fill="none"/><path d="M2 14.9092H8" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M40 14.9092H46H40Z" fill="none"/><path d="M40 14.9092H46" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M2 24H8H2Z" fill="none"/><path d="M2 24H8" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M40 24H46H40Z" fill="none"/><path d="M40 24H46" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M2 33.0908H8H2Z" fill="none"/><path d="M2 33.0908H8" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M40 33.0908H46H40Z" fill="none"/><path d="M40 33.0908H46" stroke="currentColor" stroke-width="4"/></svg>

### Server
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M44 4H4V20H44V4Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M44 28H4V44H44V28Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M13 10H11C10.4477 10 10 10.4477 10 11V13C10 13.5523 10.4477 14 11 14H13C13.5523 14 14 13.5523 14 13V11C14 10.4477 13.5523 10 13 10Z" fill="currentColor"/><path d="M13 34H11C10.4477 34 10 34.4477 10 35V37C10 37.5523 10.4477 38 11 38H13C13.5523 38 14 37.5523 14 37V35C14 34.4477 13.5523 34 13 34Z" fill="currentColor"/><path d="M21 10H19C18.4477 10 18 10.4477 18 11V13C18 13.5523 18.4477 14 19 14H21C21.5523 14 22 13.5523 22 13V11C22 10.4477 21.5523 10 21 10Z" fill="currentColor"/><path d="M21 34H19C18.4477 34 18 34.4477 18 35V37C18 37.5523 18.4477 38 19 38H21C21.5523 38 22 37.5523 22 37V35C22 34.4477 21.5523 34 21 34Z" fill="currentColor"/></svg>

### Wifi
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M4 18.9653C4.5888 18.4073 5.19522 17.8786 5.8174 17.3792C17.0371 8.37423 33.3821 8.90292 44 18.9653" stroke="currentColor" stroke-width="4"/><path d="M38 25.799C30.268 18.067 17.732 18.067 10 25.799" stroke="currentColor" stroke-width="4"/><path d="M32 32.3137C27.5817 27.8954 20.4183 27.8954 16 32.3137" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M24 40C25.3807 40 26.5 38.8807 26.5 37.5C26.5 36.1193 25.3807 35 24 35C22.6193 35 21.5 36.1193 21.5 37.5C21.5 38.8807 22.6193 40 24 40Z" fill="currentColor"/></svg>

### Api
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M37 22.0001L34 25.0001L23 14.0001L26 11.0001C27.5 9.50002 33 7.00005 37 11.0001C41 15.0001 38.5 20.5 37 22.0001Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M42 6L37 11" stroke="currentColor" stroke-width="4"/><path d="M11 25.9999L14 22.9999L25 33.9999L22 36.9999C20.5 38.5 15 41 11 36.9999C7 32.9999 9.5 27.5 11 25.9999Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M23 32L27 28" stroke="currentColor" stroke-width="4"/><path d="M6 42L11 37" stroke="currentColor" stroke-width="4"/><path d="M16 25L20 21" stroke="currentColor" stroke-width="4"/></svg>

### Branch
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M40 28C42.2091 28 44 26.2091 44 24C44 21.7909 42.2091 20 40 20C37.7909 20 36 21.7909 36 24C36 26.2091 37.7909 28 40 28Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M9 12C11.2091 12 13 10.2091 13 8C13 5.79086 11.2091 4 9 4C6.79086 4 5 5.79086 5 8C5 10.2091 6.79086 12 9 12Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M9 44C11.2091 44 13 42.2091 13 40C13 37.7909 11.2091 36 9 36C6.79086 36 5 37.7909 5 40C5 42.2091 6.79086 44 9 44Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M9 12V36V24.0083H36" stroke="currentColor" stroke-width="4"/></svg>

### GithubOne
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M29.3444 30.4765C31.7481 29.977 33.9292 29.1108 35.6247 27.8391C38.5202 25.6676 40 22.3136 40 18.9999C40 16.6752 39.1187 14.505 37.5929 12.6668C36.7427 11.6425 39.2295 3.99989 37.02 5.02919C34.8105 6.05848 31.5708 8.33679 29.8726 7.83398C28.0545 7.29565 26.0733 6.99989 24 6.99989C22.1992 6.99989 20.4679 7.22301 18.8526 7.6344C16.5046 8.23237 14.2591 5.99989 12 5.02919C9.74086 4.05848 10.9736 11.9632 10.3026 12.7944C8.84119 14.6051 8 16.7288 8 18.9999C8 22.3136 9.79086 25.6676 12.6863 27.8391C14.6151 29.2857 17.034 30.2076 19.7401 30.6619" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M19.7397 30.6619C18.5812 31.937 18.002 33.1478 18.002 34.2944C18.002 35.441 18.002 38.3464 18.002 43.0106" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M29.3446 30.4766C30.4423 31.9174 30.9912 33.211 30.9912 34.3576C30.9912 35.5042 30.9912 38.3885 30.9912 43.0107" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M6 31.2155C6.89887 31.3254 7.56554 31.7387 8 32.4554C8.65169 33.5303 11.0742 37.518 13.8251 37.518C15.6591 37.518 17.0515 37.518 18.0024 37.518" stroke="currentColor" stroke-width="4" stroke-linecap="round"/></svg>

### Bug
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 42C36 42 38 31.5324 38 28C38 24.8379 38 20.1712 38 14H10C10 17.4423 10 22.109 10 28C10 31.4506 12 42 24 42Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M4 8L10 14" stroke="currentColor" stroke-width="4"/><path d="M44 8L38 14" stroke="currentColor" stroke-width="4"/><path d="M4 27H10" stroke="currentColor" stroke-width="4"/><path d="M44 27H38" stroke="currentColor" stroke-width="4"/><path d="M7 44L13 38" stroke="currentColor" stroke-width="4"/><path d="M41 44L35 38" stroke="currentColor" stroke-width="4"/><path d="M24 42V14" stroke="currentColor" stroke-width="4"/><path d="M14.9204 39.0407C17.0024 40.783 19.9244 41.9998 23.9999 41.9998C28.1112 41.9998 31.0487 40.7712 33.1341 39.0137" stroke="currentColor" stroke-width="4"/><path d="M32 12.3333C32 7.73096 28.4183 4 24 4C19.5817 4 16 7.73096 16 12.3333V14H32V12.3333Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Tool
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M44 16C44 22.6274 38.6274 28 32 28C29.9733 28 28.0639 27.4975 26.3896 26.6104L9 44L4 39L21.3896 21.6104C20.5025 19.9361 20 18.0267 20 16C20 9.37258 25.3726 4 32 4C34.0267 4 35.9361 4.50245 37.6104 5.38959L30 13L35 18L42.6104 10.3896C43.4975 12.0639 44 13.9733 44 16Z" fill="none" stroke="currentColor" stroke-width="4"/></svg>

### Config
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 4L18 10H10V18L4 24L10 30V38H18L24 44L30 38H38V30L44 24L38 18V10H30L24 4Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M24 30C27.3137 30 30 27.3137 30 24C30 20.6863 27.3137 18 24 18C20.6863 18 18 20.6863 18 24C18 27.3137 20.6863 30 24 30Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Plug
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M6 14H42V24C38 32 32 36 24 36C16 36 10 32 6 24V14Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M33 34L32 44H16L15 34" stroke="currentColor" stroke-width="4"/><path d="M22 24H26" stroke="currentColor" stroke-width="4"/><path d="M16 4L16 12" stroke="currentColor" stroke-width="4"/><path d="M32 4V12" stroke="currentColor" stroke-width="4"/></svg>

### PlugOne
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><rect x="12" y="12" width="24" height="24" rx="3" fill="none" stroke="currentColor" stroke-width="4"/><path d="M24 36V41C24 42.6569 22.6569 44 21 44H8" stroke="currentColor" stroke-width="4"/><path d="M20 12V4" stroke="currentColor" stroke-width="4"/><path d="M28 12V4" stroke="currentColor" stroke-width="4"/><path d="M22 24H26" stroke="currentColor" stroke-width="4"/></svg>

### Robot
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><rect x="9" y="17" width="30" height="26" rx="2" stroke="currentColor" stroke-width="4"/><path d="M33 9L28 17" stroke="currentColor" stroke-width="4"/><path d="M15 9L20 17" stroke="currentColor" stroke-width="4"/><circle cx="34" cy="7" r="2" stroke="currentColor" stroke-width="4"/><circle cx="14" cy="7" r="2" stroke="currentColor" stroke-width="4"/><rect x="16" y="24" width="16" height="8" rx="4" fill="none" stroke="currentColor" stroke-width="4"/><path d="M9 24H4V34H9" stroke="currentColor" stroke-width="4"/><path d="M39 24H44V34H39" stroke="currentColor" stroke-width="4"/></svg>

### Magic
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M20.1005 8.1005L24.3431 12.3431M30 4V10V4ZM39.8995 8.1005L35.6569 12.3431L39.8995 8.1005ZM44 18H38H44ZM39.8995 27.8995L35.6569 23.6569L39.8995 27.8995ZM30 32V26V32ZM20.1005 27.8995L24.3431 23.6569L20.1005 27.8995ZM16 18H22H16Z" stroke="currentColor" stroke-width="4"/><path d="M29.5856 18.4143L5.54395 42.4559" stroke="currentColor" stroke-width="4"/></svg>

### Cube
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M15.5 9L7 14V24V34L15.5 39L24 44L32.5001 39L41 34V24V14L32.5001 9L24 4L15.5 9Z" stroke="currentColor" stroke-width="4"/><path d="M41 14L24 24" stroke="currentColor" stroke-width="4"/><path d="M7 14L24 24" stroke="currentColor" stroke-width="4"/><path d="M24 44V24" stroke="currentColor" stroke-width="4"/><path d="M32 19L32 39" stroke="currentColor" stroke-width="4"/><path d="M41 24L24 34" stroke="currentColor" stroke-width="4"/><path d="M24 34L7 24" stroke="currentColor" stroke-width="4"/><path d="M16 39L16 19" stroke="currentColor" stroke-width="4"/><path d="M32 9L16 19" stroke="currentColor" stroke-width="4"/><path d="M32 19L16 9" stroke="currentColor" stroke-width="4"/></svg>

### Layers
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M4 11.9143L24 19L44 11.9143L24 5L4 11.9143Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M4 20L24 27L44 20" stroke="currentColor" stroke-width="4"/><path d="M4 28L24 35L44 28" stroke="currentColor" stroke-width="4"/><path d="M4 36L24 43L44 36" stroke="currentColor" stroke-width="4"/></svg>

### Key
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M22.8682 24.2982C25.4105 26.7935 26.4138 30.4526 25.4971 33.8863C24.5805 37.32 21.8844 40.0019 18.4325 40.9137C14.9806 41.8256 11.3022 40.8276 8.79375 38.2986C5.02208 34.4141 5.07602 28.2394 8.91499 24.4206C12.754 20.6019 18.9613 20.5482 22.8664 24.3L22.8682 24.2982Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M23 24L40 7" stroke="currentColor" stroke-width="4"/><path d="M30.3052 16.9001L35.7337 22.3001L42.0671 16.0001L36.6385 10.6001L30.3052 16.9001Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Shield
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M6 8.25564L24.0086 3L42 8.25564V19.0337C42 30.3622 34.7502 40.4194 24.0026 44.0005C13.2521 40.4195 6 30.36 6 19.0287V8.25564Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### ShieldAdd
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M6 8.25564L24.0086 3L42 8.25564V19.0337C42 30.3622 34.7502 40.4194 24.0026 44.0005C13.2521 40.4195 6 30.36 6 19.0287V8.25564Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M23.9497 14.9497V30.9497" stroke="currentColor" stroke-width="4"/><path d="M15.9497 22.9497H31.9497" stroke="currentColor" stroke-width="4"/></svg>

### Fingerprint
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M18 43V22C18 18.6863 20.6863 16 24 16C27.3137 16 30 18.6863 30 22V43" stroke="currentColor" stroke-width="4"/><path d="M12 40V22C12 15.3726 17.3726 10 24 10C30.6274 10 36 15.3726 36 22V40" stroke="currentColor" stroke-width="4"/><path d="M6 35V22C6 12.0589 14.0589 4 24 4C33.9411 4 42 12.0589 42 22V35" stroke="currentColor" stroke-width="4"/><path d="M24 44V31" stroke="currentColor" stroke-width="4"/><path d="M24 24.625V21.875" stroke="currentColor" stroke-width="4"/></svg>

### ApplicationOne
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M41 13.9997L24 4L7 13.9997V33.9998L24 44L41 33.9998V13.9997Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M16 18.9976L23.9932 24.0002L31.9951 18.9976" stroke="currentColor" stroke-width="4"/><path d="M24 24V33" stroke="currentColor" stroke-width="4"/></svg>

### Browser
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M42 18V40C42 41.1046 41.1046 42 40 42H8C6.89543 42 6 41.1046 6 40V18" stroke="currentColor" stroke-width="4"/><path d="M6 8C6 6.89543 6.89543 6 8 6H40C41.1046 6 42 6.89543 42 8V18H6V8Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path fill-rule="evenodd" clip-rule="evenodd" d="M12 14C13.1046 14 14 13.1046 14 12C14 10.8954 13.1046 10 12 10C10.8954 10 10 10.8954 10 12C10 13.1046 10.8954 14 12 14Z" fill="currentColor"/><path fill-rule="evenodd" clip-rule="evenodd" d="M18 14C19.1046 14 20 13.1046 20 12C20 10.8954 19.1046 10 18 10C16.8954 10 16 10.8954 16 12C16 13.1046 16.8954 14 18 14Z" fill="currentColor"/><path fill-rule="evenodd" clip-rule="evenodd" d="M24 14C25.1046 14 26 13.1046 26 12C26 10.8954 25.1046 10 24 10C22.8954 10 22 10.8954 22 12C22 13.1046 22.8954 14 24 14Z" fill="currentColor"/></svg>

### Application
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M40.0391 22V42H8.03906V22" stroke="currentColor" stroke-width="4"/><path d="M5.84231 13.7766C4.31276 17.7377 7.26307 22 11.5092 22C14.8229 22 17.5276 19.3137 17.5276 16C17.5276 19.3137 20.2139 22 23.5276 22H24.546C27.8597 22 30.546 19.3137 30.546 16C30.546 19.3137 33.2518 22 36.5655 22C40.8139 22 43.767 17.7352 42.2362 13.7723L39.2337 6H8.84523L5.84231 13.7766Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

## People and places

### User
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><circle cx="24" cy="12" r="8" fill="none" stroke="currentColor" stroke-width="4"/><path d="M42 44C42 34.0589 33.9411 26 24 26C14.0589 26 6 34.0589 6 44" stroke="currentColor" stroke-width="4"/></svg>

### Peoples
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M19 20C22.866 20 26 16.866 26 13C26 9.13401 22.866 6 19 6C15.134 6 12 9.13401 12 13C12 16.866 15.134 20 19 20Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M32.6077 7C34.6405 8.2249 36.0001 10.4537 36.0001 13C36.0001 15.5463 34.6405 17.7751 32.6077 19" stroke="currentColor" stroke-width="4"/><path d="M4 40.8V42H34V40.8C34 36.3196 34 34.0794 33.1281 32.3681C32.3611 30.8628 31.1372 29.6389 29.6319 28.8719C27.9206 28 25.6804 28 21.2 28H16.8C12.3196 28 10.0794 28 8.36808 28.8719C6.86278 29.6389 5.63893 30.8628 4.87195 32.3681C4 34.0794 4 36.3196 4 40.8Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M43.9999 42.0001V40.8001C43.9999 36.3197 43.9999 34.0795 43.128 32.3682C42.361 30.8629 41.1371 29.6391 39.6318 28.8721" stroke="currentColor" stroke-width="4"/></svg>

### People
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 20C27.866 20 31 16.866 31 13C31 9.13401 27.866 6 24 6C20.134 6 17 9.13401 17 13C17 16.866 20.134 20 24 20Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M6 40.8V42H42V40.8C42 36.3196 42 34.0794 41.1281 32.3681C40.3611 30.8628 39.1372 29.6389 37.6319 28.8719C35.9206 28 33.6804 28 29.2 28H18.8C14.3196 28 12.0794 28 10.3681 28.8719C8.86278 29.6389 7.63893 30.8628 6.87195 32.3681C6 34.0794 6 36.3196 6 40.8Z" fill="none" stroke="currentColor" stroke-width="4"/></svg>

### Home
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M9 18V42H39V18L24 6L9 18Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M19 29V42H29V29H19Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M9 42H39" stroke="currentColor" stroke-width="4" stroke-linecap="round"/></svg>

### Local
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M9.85786 32.7574C6.23858 33.8432 4 35.3432 4 37C4 40.3137 12.9543 43 24 43C35.0457 43 44 40.3137 44 37C44 35.3432 41.7614 33.8432 38.1421 32.7574" stroke="currentColor" stroke-width="4"/><path d="M24 35C24 35 37 26.504 37 16.6818C37 9.67784 31.1797 4 24 4C16.8203 4 11 9.67784 11 16.6818C11 26.504 24 35 24 35Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M24 22C26.7614 22 29 19.7614 29 17C29 14.2386 26.7614 12 24 12C21.2386 12 19 14.2386 19 17C19 19.7614 21.2386 22 24 22Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Globe
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M37.8261 4C41.6276 7.58886 44 12.6753 44 18.3158C44 29.1871 35.1871 38 24.3158 38C18.6753 38 13.5889 35.6276 10 31.8261" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M24 32C31.732 32 38 25.732 38 18C38 10.268 31.732 4 24 4C16.268 4 10 10.268 10 18C10 25.732 16.268 32 24 32Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M24 38V44" stroke="currentColor" stroke-width="4"/><path d="M18 44H30" stroke="currentColor" stroke-width="4"/></svg>

### Earth
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path fill-rule="evenodd" clip-rule="evenodd" d="M24 44C35.0457 44 44 35.0457 44 24C44 12.9543 35.0457 4 24 4C12.9543 4 4 12.9543 4 24C4 35.0457 12.9543 44 24 44Z" stroke="currentColor" stroke-width="4"/><path d="M4 24H44" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M24 44C28.4183 44 32 35.0457 32 24C32 12.9543 28.4183 4 24 4C19.5817 4 16 12.9543 16 24C16 35.0457 19.5817 44 24 44Z" stroke="currentColor" stroke-width="4"/><path d="M9.85791 10.1421C13.4772 13.7614 18.4772 16 24 16C29.5229 16 34.5229 13.7614 38.1422 10.1421" stroke="currentColor" stroke-width="4"/><path d="M38.1422 37.8579C34.5229 34.2386 29.5229 32 24 32C18.4772 32 13.4772 34.2386 9.85791 37.8579" stroke="currentColor" stroke-width="4"/></svg>

### Compass
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M12 44L22.6875 15.5" stroke="currentColor" stroke-width="4"/><path d="M36 44L25.3125 15.5" stroke="currentColor" stroke-width="4"/><circle cx="24" cy="12" r="4" fill="none" stroke="currentColor" stroke-width="4"/><path d="M37.57 33C33.6618 35.5307 29.0024 37 23.9998 37C18.9973 37 14.3379 35.5307 10.4297 33" stroke="currentColor" stroke-width="4"/><path d="M24 8V4" stroke="currentColor" stroke-width="4"/></svg>

### Flag
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M8 44H12H16" stroke="currentColor" stroke-width="4"/><path d="M12 44V4" stroke="currentColor" stroke-width="4"/><path d="M40 6H12V22H40L36 14L40 6Z" fill="none" stroke="currentColor" stroke-width="4"/></svg>

### Mark
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M11 6V42" stroke="currentColor" stroke-width="4"/><path d="M11 9H25L32 12H39C40.1046 12 41 12.8954 41 14V31C41 32.1046 40.1046 33 39 33H32L25 30H11V9Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M7 42H15" stroke="currentColor" stroke-width="4"/></svg>

### Trophy
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 30C30.6274 30 36 24.4694 36 17.6471V4H12V17.6471C12 24.4694 17.3726 30 24 30Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path fill-rule="evenodd" clip-rule="evenodd" d="M12 21V11H4C4 17.6667 8 21 12 21Z" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M36 21V11H44C44 17.6667 40 21 36 21Z" stroke="currentColor" stroke-width="4"/><path d="M24 32V36" stroke="currentColor" stroke-width="4"/><path d="M15 42L18.69 36H29.0425L33 42H15Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Target
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M21.4172 18.5828C19.3962 19.5481 18 21.6109 18 23.9999C18 27.3136 20.6863 29.9999 24 29.9999C26.389 29.9999 28.4519 28.6037 29.4172 26.5828" stroke="currentColor" stroke-width="4"/><path d="M28.2793 11.7207C26.9392 11.2538 25.4992 11 24 11C16.8203 11 11 16.8203 11 24C11 31.1797 16.8203 37 24 37C31.1797 37 37 31.1797 37 24C37 22.5008 36.7462 21.0608 36.2793 19.7207" stroke="currentColor" stroke-width="4"/><path d="M33.5675 6.43255C30.7255 4.88151 27.4657 4 24 4C12.9543 4 4 12.9543 4 24C4 35.0457 12.9543 44 24 44C35.0457 44 44 35.0457 44 24C44 20.5343 43.1185 17.2745 41.5675 14.4325" stroke="currentColor" stroke-width="4"/><path d="M44 4L24 24" stroke="currentColor" stroke-width="4"/></svg>

### Rocket
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M18.705 7.89449L24 4L29.295 7.89449C32.8819 10.5327 35 14.7198 35 19.1725V37H13V19.1725C13 14.7198 15.1181 10.5327 18.705 7.89449Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path fill-rule="evenodd" clip-rule="evenodd" d="M13 17L7 23V31L13 28V17Z" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M35 17L41 23V31L35 28V17Z" stroke="currentColor" stroke-width="4"/><path d="M18 39V42" stroke="currentColor" stroke-width="4"/><path d="M24 39V44" stroke="currentColor" stroke-width="4"/><path d="M30 39V42" stroke="currentColor" stroke-width="4"/></svg>

### Lightning
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M19 4H37L26 18H41L17 44L22 25H8L19 4Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Fire
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 44C32.2347 44 38.9998 37.4742 38.9998 29.0981C38.9998 27.0418 38.8953 24.8375 37.7555 21.4116C36.6157 17.9858 36.3861 17.5436 35.1809 15.4279C34.666 19.7454 31.911 21.5448 31.2111 22.0826C31.2111 21.5231 29.5445 15.3359 27.0176 11.6339C24.537 8 21.1634 5.61592 19.1853 4C19.1853 7.06977 18.3219 11.6339 17.0854 13.9594C15.8489 16.2849 15.6167 16.3696 14.0722 18.1002C12.5278 19.8308 11.8189 20.3653 10.5274 22.4651C9.23596 24.565 9 27.3618 9 29.4181C9 37.7942 15.7653 44 24 44Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Sun
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M9.15039 9.15088L11.3778 11.3783" stroke="currentColor" stroke-width="4"/><path d="M3 24H6.15" stroke="currentColor" stroke-width="4"/><path d="M9.15039 38.8495L11.3778 36.6221" stroke="currentColor" stroke-width="4"/><path d="M38.8495 38.8495L36.6221 36.6221" stroke="currentColor" stroke-width="4"/><path d="M44.9996 24H41.8496" stroke="currentColor" stroke-width="4"/><path d="M38.8495 9.15088L36.6221 11.3783" stroke="currentColor" stroke-width="4"/><path d="M24 3V6.15" stroke="currentColor" stroke-width="4"/><path d="M24 36C30.6274 36 36 30.6274 36 24C36 17.3726 30.6274 12 24 12C17.3726 12 12 17.3726 12 24C12 30.6274 17.3726 36 24 36Z" fill="currentColor" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M24 45.0001V41.8501" stroke="currentColor" stroke-width="4"/></svg>

### Moon
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M28.0527 4.41085C22.5828 5.83695 18.5455 10.8106 18.5455 16.7273C18.5455 23.7564 24.2436 29.4545 31.2727 29.4545C37.1894 29.4545 42.1631 25.4172 43.5891 19.9473C43.8585 21.256 44 22.6115 44 24C44 35.0457 35.0457 44 24 44C12.9543 44 4 35.0457 4 24C4 12.9543 12.9543 4 24 4C25.3885 4 26.744 4.14149 28.0527 4.41085Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Water
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M9 29C11.7614 29 14 26.7614 14 24C14 26.7614 16.2386 29 19 29C21.7614 29 24 26.7614 24 24C24 26.7614 26.2386 29 29 29C31.7614 29 34 26.7614 34 24C34 26.7614 36.2386 29 39 29C41.7614 29 44 26.7614 44 24C44 35.0457 35.0457 44 24 44C12.9543 44 4 35.0457 4 24C4 26.7614 6.23858 29 9 29Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M28 13C28 15.2091 26.2091 17 24 17C21.7909 17 20 15.2091 20 13C20 10.7909 24 4 24 4C24 4 28 10.7909 28 13Z" fill="none" stroke="currentColor" stroke-width="4"/></svg>

### Tree
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M13.0448 14C13.5501 8.3935 18.262 4 24 4C29.738 4 34.4499 8.3935 34.9552 14H35C39.9706 14 44 18.0294 44 23C44 27.9706 39.9706 32 35 32H13C8.02944 32 4 27.9706 4 23C4 18.0294 8.02944 14 13 14H13.0448Z" stroke="currentColor" stroke-width="4"/><path d="M24 28L29 23" stroke="currentColor" stroke-width="4"/><path d="M24 25L18 19" stroke="currentColor" stroke-width="4"/><path d="M24 44V18" stroke="currentColor" stroke-width="4"/></svg>

### Leaf
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M37 24C37 38.0938 24 44 24 44C24 44 11 39.375 11 24C11 8.625 24 4 24 4C24 4 37 9.90625 37 24Z" stroke="currentColor" stroke-width="4"/><path d="M24 36L29 31" stroke="currentColor" stroke-width="4"/><path d="M24 29L19 24" stroke="currentColor" stroke-width="4"/><path d="M24 23L29 18" stroke="currentColor" stroke-width="4"/><path d="M24 44V14" stroke="currentColor" stroke-width="4"/></svg>

### Brain
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M19.036 44.0002C18.0561 40.8046 16.5778 38.4223 14.6011 36.8533C11.636 34.4998 6.92483 35.9625 5.18458 33.535C3.44433 31.1074 6.40382 26.6432 7.44234 24.0091C8.48086 21.3751 3.46179 20.4437 4.04776 19.6959C4.43842 19.1974 6.97471 17.7588 11.6567 15.3802C12.987 7.79356 17.9008 4.00024 26.3982 4.00024C39.1441 4.00024 44 14.8062 44 21.6791C44 28.5521 38.1201 35.9564 29.7441 37.5529C28.9951 38.6437 30.0754 40.7928 32.9848 44.0002" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M19.4997 14.5001C18.8464 17.0344 19.0408 18.8139 20.0829 19.8386C21.125 20.8634 22.9011 21.5335 25.4112 21.849C24.8417 25.1177 25.5361 26.6512 27.4942 26.4494C29.4524 26.2476 30.6289 25.434 31.0239 24.0084C34.0842 24.8685 35.7428 24.1487 35.9997 21.849C36.3852 18.3994 34.525 15.6476 33.7624 15.6476C32.9997 15.6476 31.0239 15.5548 31.0239 14.5001C31.0239 13.4453 28.7159 12.8494 26.6329 12.8494C24.5499 12.8494 25.8035 11.4453 22.9432 12.0001C21.0363 12.3699 19.8885 13.2032 19.4997 14.5001Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M30.5002 25.5002C29.4833 26.1313 28.0878 27.1805 27.5002 28.0002C26.0313 30.0497 24.8398 31.2976 24.5791 32.6083" stroke="currentColor" stroke-width="4" stroke-linecap="round"/></svg>

### Book
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M8 40C8 36 8 10 8 10C8 6.68629 10.8654 4 14.4 4H40V36C40 36 19.9815 36 14.4 36C9.36225 36 8 36.6842 8 40Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path fill-rule="evenodd" clip-rule="evenodd" d="M12 44H40V36H12C9.79086 36 8 37.7909 8 40C8 42.2091 9.79086 44 12 44Z" stroke="currentColor" stroke-width="4"/></svg>

### BookOpen
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M5 7H16C20.4183 7 24 10.5817 24 15V42C24 38.6863 21.3137 36 18 36H5V7Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M43 7H32C27.5817 7 24 10.5817 24 15V42C24 38.6863 26.6863 36 30 36H43V7Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Message
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M44.0001 24C44.0001 35.0457 35.0458 44 24.0001 44C18.0266 44 4.00006 44 4.00006 44C4.00006 44 4.00006 29.0722 4.00006 24C4.00006 12.9543 12.9544 4 24.0001 4C35.0458 4 44.0001 12.9543 44.0001 24Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M14 18L32 18" stroke="currentColor" stroke-width="4"/><path d="M14 26H32" stroke="currentColor" stroke-width="4"/><path d="M14 34H24" stroke="currentColor" stroke-width="4"/></svg>

### Comment
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M44 6H4V36H13V41L23 36H44V6Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M14 19.5V22.5" stroke="currentColor" stroke-width="4"/><path d="M24 19.5V22.5" stroke="currentColor" stroke-width="4"/><path d="M34 19.5V22.5" stroke="currentColor" stroke-width="4"/></svg>

### Phone
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M8 30H40V42C40 43.1046 39.1046 44 38 44H10C8.89543 44 8 43.1046 8 42V30Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M40 30V6C40 4.89543 39.1046 4 38 4H10C8.89543 4 8 4.89543 8 6V30" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M22 37H26" stroke="currentColor" stroke-width="4" stroke-linecap="round"/></svg>

### Camera
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M15 12L18 6H30L33 12H15Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><rect x="4" y="12" width="40" height="30" rx="3" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M24 35C28.4183 35 32 31.4183 32 27C32 22.5817 28.4183 19 24 19C19.5817 19 16 22.5817 16 27C16 31.4183 19.5817 35 24 35Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Video
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M4 10C4 8.89543 4.89543 8 6 8H42C43.1046 8 44 8.89543 44 10V38C44 39.1046 43.1046 40 42 40H6C4.89543 40 4 39.1046 4 38V10Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M36 8V40" stroke="currentColor" stroke-width="4"/><path d="M12 8V40" stroke="currentColor" stroke-width="4"/><path d="M38 18H44" stroke="currentColor" stroke-width="4"/><path d="M38 30H44" stroke="currentColor" stroke-width="4"/><path d="M4 18H10" stroke="currentColor" stroke-width="4"/><path d="M4 16V20" stroke="currentColor" stroke-width="4"/><path d="M9 8H15" stroke="currentColor" stroke-width="4"/><path d="M9 40H15" stroke="currentColor" stroke-width="4"/><path d="M33 8H39" stroke="currentColor" stroke-width="4"/><path d="M33 40H39" stroke="currentColor" stroke-width="4"/><path d="M4 30H10" stroke="currentColor" stroke-width="4"/><path d="M4 28V32" stroke="currentColor" stroke-width="4"/><path d="M44 28V32" stroke="currentColor" stroke-width="4"/><path d="M44 16V20" stroke="currentColor" stroke-width="4"/><path d="M21 19L29 24L21 29V19Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Music
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M30 34.5C30 32.567 31.567 31 33.5 31H41V34.4C41 36.3882 39.3882 38 37.4 38H33.5C31.567 38 30 36.433 30 34.5Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M6 38.5C6 36.567 7.567 35 9.5 35H16V38.4C16 40.3882 14.3882 42 12.4 42H9.5C7.567 42 6 40.433 6 38.5Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M16 18.044V18.044L41 12.125" stroke="currentColor" stroke-width="4"/><path d="M16 38V10L41 4V33.6924" stroke="currentColor" stroke-width="4"/></svg>

### Pic
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path fill-rule="evenodd" clip-rule="evenodd" d="M5 10C5 8.89543 5.89543 8 7 8L41 8C42.1046 8 43 8.89543 43 10V38C43 39.1046 42.1046 40 41 40H7C5.89543 40 5 39.1046 5 38V10Z" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M14.5 18C15.3284 18 16 17.3284 16 16.5C16 15.6716 15.3284 15 14.5 15C13.6716 15 13 15.6716 13 16.5C13 17.3284 13.6716 18 14.5 18Z" stroke="currentColor" stroke-width="4"/><path d="M15 24L20 28L26 21L43 34V38C43 39.1046 42.1046 40 41 40H7C5.89543 40 5 39.1046 5 38V34L15 24Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### Headset
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M42 30V24.4615C42 14.2655 33.9411 6 24 6C14.0589 6 6 14.2655 6 24.4615V30" stroke="currentColor" stroke-width="4"/><path d="M34 32C34 29.7909 35.7909 28 38 28H42V42H38C35.7909 42 34 40.2091 34 38V32Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M42 32H44C45.1046 32 46 32.8954 46 34V36C46 37.1046 45.1046 38 44 38H42V32Z" fill="currentColor"/><path d="M6 32H4C2.89543 32 2 32.8954 2 34V36C2 37.1046 2.89543 38 4 38H6V32Z" fill="currentColor"/><path d="M6 28H10C12.2091 28 14 29.7909 14 32V38C14 40.2091 12.2091 42 10 42H6V28Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/></svg>

### VolumeNotice
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M24 6V42C17 42 11.7985 32.8391 11.7985 32.8391H6C4.89543 32.8391 4 31.9437 4 30.8391V17.0108C4 15.9062 4.89543 15.0108 6 15.0108H11.7985C11.7985 15.0108 17 6 24 6Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M32 15L32 15C32.6232 15.5565 33.1881 16.1797 33.6841 16.8588C35.1387 18.8504 36 21.3223 36 24C36 26.6545 35.1535 29.1067 33.7218 31.0893C33.2168 31.7885 32.6391 32.4293 32 33" stroke="currentColor" stroke-width="4"/><path d="M34.2359 41.1857C40.0836 37.6953 44 31.305 44 24C44 16.8085 40.2043 10.5035 34.507 6.97906" stroke="currentColor" stroke-width="4" stroke-linecap="round"/></svg>

### Translate
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M28.2857 37H39.7143M42 42L39.7143 37L42 42ZM26 42L28.2857 37L26 42ZM28.2857 37L34 24L39.7143 37H28.2857Z" stroke="currentColor" stroke-width="4"/><path d="M16 6L17 9" stroke="currentColor" stroke-width="4"/><path d="M6 11H28" stroke="currentColor" stroke-width="4"/><path d="M10 16C10 16 11.7895 22.2609 16.2632 25.7391C20.7368 29.2174 28 32 28 32" stroke="currentColor" stroke-width="4"/><path d="M24 11C24 11 22.2105 19.2174 17.7368 23.7826C13.2632 28.3478 6 32 6 32" stroke="currentColor" stroke-width="4"/></svg>

### Wallet
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path fill-rule="evenodd" clip-rule="evenodd" d="M17.982 11.9689L31.7846 4L36.397 11.9889L17.982 11.9689Z" stroke="currentColor" stroke-width="4"/><path d="M4 14C4 12.8954 4.89543 12 6 12H42C43.1046 12 44 12.8954 44 14V42C44 43.1046 43.1046 44 42 44H6C4.89543 44 4 43.1046 4 42V14Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M35.25 33H44V23H35.25C32.3505 23 30 25.2386 30 28C30 30.7614 32.3505 33 35.25 33Z" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M44 16.5V40.5" stroke="currentColor" stroke-width="4" stroke-linecap="round"/></svg>

### Currency
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M19 16L24 22L29 16" stroke="currentColor" stroke-width="4"/><path d="M9 13.9999C9 13.9999 16.5 2.49984 29.5 6.99986C42.5 11.4999 42 24.4999 42 24.4999" stroke="currentColor" stroke-width="4"/><path d="M39 34C39 34 33 45 19.5 41.5C6 38 6 24 6 24" stroke="currentColor" stroke-width="4"/><path d="M42 8V24" stroke="currentColor" stroke-width="4"/><path d="M6 24L6 40" stroke="currentColor" stroke-width="4"/><path d="M18 28H30" stroke="currentColor" stroke-width="4"/><path d="M18 22H30" stroke="currentColor" stroke-width="4"/><path d="M24 22V34" stroke="currentColor" stroke-width="4"/></svg>

### ShoppingCart
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M39 32H13L8 12H44L39 32Z" fill="none"/><path d="M3 6H6.5L8 12M8 12L13 32H39L44 12H8Z" stroke="currentColor" stroke-width="4"/><circle cx="13" cy="39" r="3" stroke="currentColor" stroke-width="4"/><circle cx="39" cy="39" r="3" stroke="currentColor" stroke-width="4"/><path d="M22 22H30" stroke="currentColor" stroke-width="4"/><path d="M26 26V18" stroke="currentColor" stroke-width="4"/></svg>

### Gift
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M41 44V20H7V44H41Z" fill="none" stroke="currentColor" stroke-width="4"/><path d="M24 44V20" stroke="currentColor" stroke-width="4"/><path d="M41 44H7" stroke="currentColor" stroke-width="4"/><rect x="4" y="12" width="40" height="8" fill="none" stroke="currentColor" stroke-width="4" stroke-linejoin="round"/><path d="M16 4L24 12L32 4" stroke="currentColor" stroke-width="4"/></svg>

### Heart
<svg viewBox="0 0 48 48" fill="none" stroke-linecap="round" stroke-linejoin="round"><path d="M14.5397 20.0187C12.8522 17.9435 11.2675 17.498 9.78564 18.6822C7.5629 20.4584 6.92453 26.6497 8.71324 32.1087C10.502 37.5678 13.9801 45.0018 21.0016 45.0018C28.0231 45.0018 29.684 37.5223 32.5485 33.0002C35.413 28.4781 36.9285 24.1153 34.1208 18.6822" stroke="currentColor" stroke-width="4"/><path d="M11 18.037C9.29707 15.4429 7.96374 13.4307 6.99996 12.0003C5.5543 9.85474 9.25107 7.08175 11 8.96818C12.1659 10.2258 13.7148 12.0781 15.6466 14.5251" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M15.0236 25.6397C14.5391 19.576 14.9333 15.6277 16.2062 13.7948C18.1155 11.0456 21.6631 10.0032 25.0035 10.0032C26.9924 10.0032 28.8087 10.8503 30.4525 12.5445" stroke="currentColor" stroke-width="4"/><path fill-rule="evenodd" clip-rule="evenodd" d="M41.0003 12.6129C41.5858 14.6493 40.6294 16.5098 37.6844 16.9311C34.7393 17.3525 32.5313 18.8334 30.9388 20.0792C29.3463 21.3249 26.4983 25.1047 25.9361 27.0024C25.3738 28.9001 22.1602 27.1548 21.2971 26.3972C20.434 25.6395 19.5855 23.9807 21.2971 22.2458C23.0086 20.5109 22.6383 20.1647 22.6383 18.4053C22.6383 16.646 32.0003 10.8264 37.2729 10.2942C38.4449 10.2258 40.4147 10.5765 41.0003 12.6129Z" stroke="currentColor" stroke-width="4"/><path d="M23.0078 4.00024V9.26294" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M20.3066 10.7179C17.2888 6.92544 14.8555 4.80879 13.0068 4.36792" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M17.0039 7.02904L17.9944 2.96167" stroke="currentColor" stroke-width="4" stroke-linecap="round"/><path d="M35.6128 10.7175C35.2905 11.822 35.2905 12.8576 35.6128 13.8242C35.935 14.7909 36.6255 15.8265 37.6842 16.931" stroke="currentColor" stroke-width="4" stroke-linecap="round"/></svg>
