---
layout: default
title: Can Do privacy policy
permalink: /privacy/
---

# Can Do privacy policy

Last updated: 7 November 2026

Can Do is an application (app) for planning routes and recording runs. You can use
the app without an account.

Can Do is operated by Lachy Wharton.

Privacy contact: [candoappsupport@gmail.com](mailto:candoappsupport@gmail.com).

## Your runs and routes

Can Do stores recorded GPS points, step readings, barometer readings, run
times and run history on your phone. It also stores your planned routes
and preferences there. The run recording directory is excluded from the
phone's backup. Can Do has no account service or cloud run sync.

Some information about your runs leaves your phone: the app sends run totals (such as the total distance moved) to our analytics service, and map services receive information about places
you view or plan routes through, as explained below.

## Location and motion permissions

With your permission, Can Do uses location to centre the map and record a
run. Location recording continues during a run, including pauses, with the
app in the background or the phone locked. Motion & Fitness access supports
step readings, auto-pause and elevation features.

You can change these permissions in iPhone Settings. Some features will not
work without them. These permissions are separate from analytics collection.

## Maps and elevation

Can Do uses Mapbox to display maps, find paths and estimate elevation changes for routes. Mapbox receives requested map areas and coordinates used in route requests. Making map pictures for run history also requests map data for those areas. The run trace is drawn over the pictures on your phone.

Mapbox receives connection information, including your IP address, and may receive SDK identifiers and app or device information for service operation, billing and security. Can Do disables Mapbox's optional location telemetry. This does not stop requests needed to provide maps and routes.

For planned elevation, Can Do downloads parts of public Copernicus terrain files hosted on Amazon Web Services (AWS). AWS receives your IP address and requests for the relevant terrain area. Your recorded run is not uploaded to AWS.

See [Mapbox's privacy policy](https://www.mapbox.com/legal/privacy) and [AWS's privacy notice](https://aws.amazon.com/privacy/).

## Analytics and crash reports

We use PostHog to understand app use and find problems. It receives:

- A random install ID, event times and app, device, operating system and build information. The ID is randomly assigned and groups activity from the same installation.
- Interactions such as opening screens, planning routes, changing settings and starting, saving or discarding runs.
- Fitness totals, including run distance, duration, elevation and pace measurements, plus run counts and weekly totals. Discarding a run does not prevent its totals from being sent as analytics.
- Performance and diagnostic information, such as response times, battery levels and errors.
- Crash reports, when "Help improve Can Do" is on (see Session replay and crash reports).

**Can Do excludes recorded GPS traces and route coordinates from the product analytics it sends to PostHog.**

The install ID is stored in the iPhone Keychain. It may survive deleting and
reinstalling the app. Uninstalling does not delete data already sent to PostHog.

Can Do is configured to remove coordinate and access-token text from
JavaScript analytics and error events. Native crash reports follow a
separate path and can contain technical system information. We do not send
recorded GPS traces or raw step and barometer readings to PostHog. PostHog
receives an IP address to handle the connection; our project is configured to
keep client IP addresses out of stored events and not derive a location from them.

## Session replay and crash reports

Session replay and crash reports are on unless you turn them off. You can turn
them off with "Help improve Can Do" on the first screen of the app. When replay
is on, PostHog records app interactions, which lets us review how you use the app
and how the app behaved. The main map, run map pictures and text inputs are masked
in replays. Other visible information can be recorded, including run dates,
distances, times, paces, elevation charts and summaries. Replay does not record
microphone audio or the camera. Network request and console log recording are
disabled.

## How we use and share information

We use this information to operate Can Do, understand which features help
runners and fix reliability and performance problems. We do not sell your
data, show advertisements or use your data for advertising across other
companies' apps or websites.

PostHog processes our project data in its EU hosting region in Frankfurt,
Germany. Mapbox processes data in the United States and other countries.
AWS serves terrain downloads. Their service providers may also process
information outside Australia. See [PostHog's privacy information](https://posthog.com/docs/privacy).

### TestFlight users

Apple collects TestFlight crash logs and usage information and shares them
with us. Feedback you submit is also shared with us and may include your
name, email and screenshots. We use it to improve Can Do. See
[TestFlight and privacy](https://www.apple.com/legal/privacy/data/en/test-flight/).

### Exporting and sharing

If you export and share a route or run file, it can contain precise locations.
The recipient or service you choose to send it to receives it. If you send it to us for
support, we receive its contents. **Share it only with people you trust.**

## Retention, access and deletion

Recorded runs remain on your phone while you keep the app and its data.
Deleting the app removes local app data, but does not necessarily remove
the Keychain install ID, exported files or data held by service providers.
Cached map pictures expire after 30 days and can be made again.

Analytics events and related information may remain in PostHog for a year or
longer. Session recordings are normally kept for one month. Deleting Can Do
does not automatically delete information already sent to PostHog.

Mapbox normally retains IP addresses for 30 days, with exceptions for
investigations; other retention periods depend on purpose.
AWS request handling is governed by its privacy notice.

Contact us to request access, correction or deletion of information we hold,
or to raise a complaint. We may need enough information to find the right
installation, because the app does not collect your name or email at sign-up.
Do not send a full run export just to identify yourself. We can request
deletion of the matching PostHog profile, events and recordings. Data held
independently by other providers is subject to their request procedures.
Copies you shared with others are outside Can Do's control.

## Changes

We will update this policy when the app's data practices change. The
published policy will show the date of its latest update.
