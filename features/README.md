# Features Directory #
-----------------------
- The 'features' directory should only include functionality built specifically for a client.
- Any features should have the ability to be included or excluded without breaking the core theme functionality.
- Functionality should be referenced in functions.php ( Ex. require get_template_directory() . '/features/client-feature/client-feature.php'; )
- Features should have a consistent folder structure, for example:
- client-feature
-- client-feature.php
-- css
-- js
-- images