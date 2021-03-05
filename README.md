Skype for Business Photo Editor
============================================

This is a PowerShell based tool used to batch resize, crop and filter images for use with Skype for Business server. This project may also be useful for others as a starting point for building other image processing tools using PowerShell.

**Tool Features:**


  *  Bulk conversion of a folder full of images files.
  *  Custom coded image processing!
  *  Manual editing and cropping of individual files. Simply Drag and Drop an image into the Picture Box area and then start selecting the crop box size and position you would like your output files to be based on. Set filter options and preview their effects on the image using the “Preview Filter” button. The size of the image crop box is shown under the scaling tools to allow you to know if you are cropping to a size smaller than image you are wanting to output (to avoid accidently upwards rescaling of the images).
  *  Accepts input files in the following formats: ".jpg", ".jpeg", ".gif", ".png", ".bmp" and ".tif”. All files get converted to “.jpg” format so they can be easily imported into Exchange/AD.
  *  Smart Crop / Centre Crop modes – By ticking this box (default) my Smart Cropping algorithm will be used to discover the subject's face and crop appropriately. The Margin setting is used in conjunction with Smart Crop to determine how loose or tight the framing will be around the subject. If unticked, a simple Centre Crop Method will be used. See the Smart Crop section for more details.
  *  Filters! Since Instagram became such a big hit, filters have become a must-have for all successful software projects. So why should this one be any different? Photo filters include: Colourise (Blue, Red, Green, Yellow, Orange, Pink, Purple), Contrast (Reduce Contrast, Light Contrast Boost, Medium Contrast Boost, Mega Contrast Boost, Ultra Contrast Boost), Brightness (Reduce Brightness, Light Brightness Boost, Medium Brightness Boost, Mega Brightness Boost, Ultra Contrast Boost), Effects (Old Film, Vignette, Light Leak, Vintage, and Slide Show).
  *  Output sizes. By default the tool will output 96x96 and 648x648 sized photos. These can be turned on or off using the checkboxes in the “Image Output Settings” area of the GUI. There is also the option to create custom sized photos by ticking the custom checkbox and selecting the pixel width/height of the photos to be outputted. It is generally recommended that 96x96 files are used for uploading to Active Directory and the 648 x 648 images are uploaded to Exchange 2013.
  *  Quality Control – The quality of the jpg images that the tool will output can be changed by reducing the Quality setting between 1-100. I suggest that you never actually reduce this in the process of creating the files that you are importing via Exchange, as the quality will be further reduced by Exchange as part of the import process.


**Screen Shot:**

![Image](https://github.com/jamescussen/skype-for-business-photo-editor/raw/main/skype-for-business-photo-editor.png)

 
**For more details visit: [https://www.myteamslab.com/2015/02/photos-part-1-lync-skype-for-business.html](https://www.myteamslab.com/2015/02/photos-part-1-lync-skype-for-business.html)**
