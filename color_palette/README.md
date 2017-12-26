For Odoo Enterprise Version 11.0, this module replaces the default Apps Switcher background with a single gray image background. By replacing the image file in this module, you can further personalize the Odoo Apps Switcher page. This is a very simply module. It serves as an ideal example for those who are learning how to build modules with Odoo.
or you want to change your own color just go to color_palette/static/src/less/variables.less
and change these:
@odoo-brand-primary: #0077cd;
@odoo-brand-optional: #4d8496;
@odoo-brand-secondary: #00ce2c;
@odoo-brand-lightsecondary: #e2e2e0;
as color you want.
