# abettershelter
Animal Shelter Management Software
Overview: This is a Wordpress plugin designed primarily for non-profit, all-volunteer rescue groups to maintain a database of rescue animals and related information: intake, status, comments, photos and profile.
Specs: Php, javascript and mysql.

I. Installation
When the plugin is installed and activated, 5 shortcodes are created. 
The system administrator must create 5 unique wordpress pages with the shortcode/permalinks below.
The page names can be custom but the shortcodes/permalinks must be exactly as written.

Page Name         Shortcode                           Permalink
Our Pets          [abettershelter]                    (url)/our-pets
Animal (Detail)   [abettershelter_animal_detail]      (url)/animal-detail
Animals (Listing) [abettershelter_animals_listing]    (url)/animals-listing
Animals (Lookup)  [abettershelter_animals_lookup]     (url)/animals-lookup
ABS (Admin)       [abettershelter_admin]              (url)/abs-admin

Note: Our Pets is the ONLY page that should be placed/referenced on the website. All other pages are called from here.
