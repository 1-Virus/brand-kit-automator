# brand-kit-automator
An automated pipeline built in n8n that generates custom business taglines and logos from a form submission, delivering them instantly to the user's inbox via Google Drive and Gmail.


How It Works
1. **The Trigger:**A user submits their Business Name and Email via an **n8n Form**.
2. **Creative Logic:**
   - **Tagline:** The AI generates a punchy, niche-specific tagline.
   - **Logo:** An AI image model creates a visual representation of the brand.
3. **Storage & Permissions:** The system uploads the logo to Google Drive and automatically sets the sharing permissions so the user can view it.
4. **Final Delivery:** A personalized email is sent via Gmail containing the tagline and the logo (as both an attachment and a Drive link).
