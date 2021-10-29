# WP_TRANSFER_STEPS

## WordPress Import/Export

### Export:
Step 1: Go to Tools and select Export.

Step 2: Once choosing which type you want to export, click Download Export File to receive the exported file.

### Import:
Step 1: Open your WordPress Dashboard, click Tools and select Import.

Step 2: Install the Importer plugin

Step 3: Import content data

Finally, please choose to Submit to run the data import process.

## Elementor Import/Export Kit
Activate the Import / Export experiment via Elementor > Settings > Experiments.

### Export:
Step 1: Go to Elementor > Tools and select Export a Template Kit

Step 2: Select Template Options and provide a name & description

Step 3: Click Export

### Import:
Step 1: Go to Elementor > Tools and select Import a Template Kit

Step 2: Drag & Drop your Export_Kit.zip file to the area provided, or click to select the .zip file from your local computer

Step 3: Choose the content you wish to be imported and click Import.


## Changing URL in Database

### CLI:
Step 1: First, log into your server via SSH.

Step 2: Next, navigate to your WordPress directory. Make sure to change your username to your Shell user.

Step 3: In your site's directory, you can use wp-cli to update the URLs using the following command.

``` shell
$ wp search-replace http://example.com https://example.com/blog --dry-run
```

**Note**: *If the changes make sense to you, then run the above command again without the dry-run call.*

### Plugin( [Better Search Replace plugin][BETTER SEARCH] ):
Step 1: In your Dashboard, navigate to the plugin under Tools > Better Search Replace.

Step 2: Click the Search/Replace tab

Step 3: In the first field titled "Search for", enter your current URL.

Step 4: In the second field titled "Replace with", enter your new URL.


[BETTER SEARCH]:https://wordpress.org/plugins/better-search-replace/
