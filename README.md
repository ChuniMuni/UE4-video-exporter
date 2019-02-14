
{_______        {_       {_______    {__      {_       {__     {__
{__    {__     {_ __     {__    {__  {__     {_ __     {__     {__
{__    {__    {_  {__    {__    {__  {__    {_  {__    {__     {__
{_______     {__   {__   {_ {__      {__   {__   {__   {______ {__
{__         {______ {__  {__  {__    {__  {______ {__  {__     {__
{__        {__       {__ {__    {__  {__ {__       {__ {__     {__
{__       {__         {__{__      {__{__{__         {__{__     {__

# Functionality

- Converts a video file to WMV 720p 25fps for playback in shipped Unreal Engine builds.

# Installation

- Unzip, ensure ffmpeg.exe is in the same folder as ue4-wmv-convert.
- If you have a 32-bit PC, delete ffmpeg.exe and rename ffmpeg.x86.exe to ffmpeg.exe.

# Usage

- Drag your video file onto to the ue4-wmv-convert.bat file provided.

# Tweaking Export Parameters

- Open "ue4-wmv-convert" in a text editor.
- "-q:v 4" determines the quality. 
- We recommend keeping this value between 2 and 5. 2 being higher quality compression, and 5 being lower quality compression

# Attributions

- Adapted from here: (https://github.com/ManzDev/video-converter-scripts/archive/master.zip) of **video-converter-scripts**.