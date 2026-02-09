# Gallery-dl Setup Guide

This application uses **gallery-dl** as an **optional external extension** to provide support for 210+ image hosting sites.

## Why External?

Gallery-dl is licensed under **GPL-2.0+** (GNU General Public License), which requires that any software bundling it must also be GPL-licensed. To maintain licensing flexibility for this application, gallery-dl is kept as an optional external dependency that users can install separately.

## Benefits of This Approach

✅ **License Compliance**: Respects GPL-2.0+ licensing requirements
✅ **User Choice**: Users can choose whether to install gallery-dl
✅ **Always Updated**: Users get the latest gallery-dl version
✅ **Transparent**: Clear separation between the app and external tools

## Installation Options

### Option 1: Using pip (Recommended)

```bash
pip install gallery-dl
```

### Option 2: Using pip with Python launcher (Windows)

```bash
py -m pip install gallery-dl
```

### Option 3: Using pipx (Isolated Installation)

```bash
pipx install gallery-dl
```

## Verification

After installation, verify gallery-dl is working:

1. Open the application
2. Go to **Settings** tab
3. Scroll to **Gallery-dl Diagnostics** section
4. Click **"Test Gallery-dl"** button

The test will:
- ✓ Check if gallery-dl is installed
- ✓ Verify the version
- ✓ Test functionality
- ✓ Count available extractors (should show 3481+)

## Testing Downloads

To test if downloads work correctly:

1. Set a download folder in Settings
2. Click **"Test Simple Download"** button
3. This will test downloading from a sample URL

## Troubleshooting

### "Gallery-dl not found"

**Solution**: Install gallery-dl using one of the methods above, then restart the application.

### "Python not found"

**Solution**: 
1. Install Python from [python.org](https://www.python.org/downloads/)
2. During installation, check "Add Python to PATH"
3. Restart your computer
4. Install gallery-dl using pip

### Test fails but gallery-dl is installed

**Solution**:
1. Open a terminal/command prompt
2. Run: `gallery-dl --version`
3. If this works, restart the application
4. If this doesn't work, reinstall gallery-dl

## Supported Sites

With gallery-dl installed, the application supports **210+ sites** including:
- Reddit
- Twitter/X
- Instagram
- DeviantArt
- Pixiv
- Danbooru
- Gelbooru
- And many more!

See the **Supported Sites** tab in the application for the full list.

## Without Gallery-dl

The application can still function without gallery-dl for:
- Direct image URLs
- Basic image downloads
- Custom extractors (if implemented)

However, for the best experience and full site support, installing gallery-dl is highly recommended.

## License Information

- **This Application**: [Your License]
- **Gallery-dl**: GPL-2.0+ (https://github.com/mikf/gallery-dl)

By keeping gallery-dl as an external dependency, users can:
- Use this application under its own license
- Optionally install gallery-dl under GPL-2.0+
- Maintain clear license boundaries

## Updates

To update gallery-dl to the latest version:

```bash
pip install --upgrade gallery-dl
```

The application will automatically detect and use the updated version.
