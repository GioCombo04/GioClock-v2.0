Changes made in GioClock-v3.0:

1- Individual channel verification:
• The script now checks if each channel is configured and exists before attempting to update it.
• If a channel is not configured or does not exist, it is simply skipped, and the script continues to function with the available channels.

2- Removal of blocking:
• The logic that disabled the script if a channel did not exist was removed. Instead, the script simply skips missing channels.

3- Conditional update:
• Each channel is updated only if it is configured and exists.
