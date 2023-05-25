## LibGuides Novanet Search Box Documentation

### Steps to Customize Novanet Search Bar

To customize the Novanet search bar, follow these steps:

1. **Customize `vid` parameter**: Modify the `vid` parameter on line 64 to customize specific settings for your institution's Novanet search.

2. **Change search input title**: On line 70, update the title displayed for the search input field to reflect your desired label.

3. **Search and replace 'stfx' with your institution**:

   - Replace 'STFX': There are 11 occurrences. Update instances related to search functionality, such as `searchSTFXNovanet()` or `vid=01NOVA_STFX:STFX` (part of the Novanet URL).
   - Replace 'StFX': There is 1 occurrence related to the search input title. Modify it accordingly.
   - Replace 'stfx': There are 18 occurrences, including references like `stfxNovanetQuery`, `stfxNovanetQueryTemp`, `div#novanet-stfx-search`, `https://stfx.novanet.ca` (for logos), and `#stfx-novanet-form`.
   
**Now you're ready to copy and paste into your Page Header HTML Code**
