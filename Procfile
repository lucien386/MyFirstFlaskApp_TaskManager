web: gunicorn
commands:
  lilypond_install:
    command: sudo apt-get lilypond
  create_folder:
    command: sudo mkdir /home/wsgi
  create_music21sc:
    command: echo '<settings encoding="utf-8"><preference name="autoDownload" value="deny" /><preference name="braillePath" /><preference name="debug" value="0" /><preference name="directoryScratch" /><preference name="graphicsPath" value="/usr/bin/eog" /><preference name="ipythonShowFormat" value="ipython.musicxml.png" /><preference name="lilypondBackend" value="ps" /><preference name="lilypondFormat" value="pdf" /><preference name="lilypondPath" value="/usr/bin/lilypond" /><preference name="lilypondVersion" /><localCorporaSettings /><localCorpusSettings /><preference name="manualCoreCorpusPath" /><preference name="midiPath" /><preference name="musescoreDirectPNGPath" /><preference name="musicxmlPath" value="/usr/bin/musescore" /><preference name="pdfPath" /><preference name="showFormat" value="musicxml" /><preference name="vectorPath" /><preference name="warnings" value="1" /><preference name="writeFormat" value="musicxml" /></settings>' > /home/wsgi/.music21rc
