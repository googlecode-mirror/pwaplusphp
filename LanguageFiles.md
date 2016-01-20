# Introduction #

PWA+PHP supports multiple languages via the config files below.  Download the file corresponding to the language you want to use on your site and place it in the lang/ folder.  Then, edit config.php to point to that file.  For example, for US English, the $SITE\_LANGUAGE file should point to "en\_us":

`$SITE_LANGUAGE="en_us";`

# Translators Needed #

This is where we need your help.  Copy the sample file below and translate it by changing the value of the variables, but not the variable names. Then [submit it](http://code.google.com/p/pwaplusphp/issues/entry?template=Language%20File%20Submission) and we'll post it on the [downloads page](http://code.google.com/p/pwaplusphp/downloads/list).

# Sample Language File #

```
<?PHP
#-----------------------------------------------------------------------------------------
# US ENGLISH LANGUAGE FILE FOR PWA+PHP
#-----------------------------------------------------------------------------------------
$LANG_MISSING_VAR_H1="Error: One or more required variables is missing from config.php!";
$LANG_MISSING_VAR_H3="Please re-run the install.php configuration script.";
$LANG_PERM_FILTER="Permission Denied.  Filter is required.";
$LANG_GALLERIES="Picasa Galleries";
$LANG_GALLERY="Gallery";
$LANG_IMAGES="images";
$LANG_PRIVATE="Private";
$LANG_PUBLIC="Public";
$LANG_WHERE="Location";
$LANG_ACCESS="Access";
$LANG_PHOTOS_IN="photos in";
$LANG_ALBUMS="albums";
$LANG_BACK="back to album list";
$LANG_PAGE="Page";
$LANG_GET="Get";
$LANG_GENERATED="Page generated by";
?>
```