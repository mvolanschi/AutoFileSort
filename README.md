# AutoFileSort

This Python script organizes files downloaded into a specified directory (downloads) into different folders based on their types. It categorizes files into video, image, and document folders (video_directory, image_directory, documents_directory). Additionally, if the file is downloaded from the "Canvas" website, it moves them to corresponding folders in the "uni" directories (uni_videos, uni_photos, uni_documents). 

The script uses macOS metadata to identify the source website of each file and then moves them accordingly using the watchdog library to monitor changes in the downloads directory.
