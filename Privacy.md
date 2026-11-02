# Aspasia Launcher — Privacy Policy

**Last updated: November 1, 2026**

## 1. Overview

Aspasia Launcher is a Chrome browser extension developed for noncommercial educational research. It enables students to open instructor-configured learning activities in Google Gemini using course-specific launch links.

This policy describes how Aspasia Launcher handles information and interacts with third-party services.

## 2. Information Processed by the Extension

Aspasia Launcher reads course identifiers and configuration parameters from designated launch links to retrieve instructor-published learning instructions.

The extension also checks whether the Gemini input field already contains text. This check is performed locally to prevent overwriting text entered by the student.

Aspasia Launcher does not intentionally collect, store, or transmit students' existing input text, Gemini conversation histories, or responses to the Aspasia configuration service.

## 3. Instructor-Published Configurations and Supabase

Aspasia Launcher uses Supabase to retrieve instructor-published course configurations and learning instructions.

Requests to Supabase contain course-identifying parameters, such as course ID, section, semester, year, and configuration version. These parameters identify the requested instructional configuration, not an individual student account.

Aspasia does not use Supabase to record student conversations or track individual learning activity responses.

Supabase may process technical information associated with requests, such as IP addresses and request metadata, for service operation, security, and infrastructure purposes. Such processing is subject to Supabase's applicable privacy practices.

Supabase Privacy Policy: https://supabase.com/privacy

## 4. Google Gemini

Aspasia Launcher inserts instructor-configured instructions into the Google Gemini input field.

Students control whether to submit those instructions to Gemini. Once submitted, the instructions and subsequent conversations are processed by Google under its applicable terms and privacy practices.

Aspasia Launcher does not control Google's collection, retention, or processing of information submitted to Gemini.

Google Privacy Policy: https://policies.google.com/privacy

## 5. Data Storage and Sharing

Aspasia Launcher does not maintain its own database of student conversations, responses, or browsing histories.

The extension does not sell student information or use student information for advertising, behavioral profiling, or marketing.

The extension communicates with the Aspasia configuration service to retrieve published instructional content. It also operates within the Google Gemini website to insert that content into the input field.

## 6. Browser Permissions

Aspasia Launcher requests browser permissions needed to perform its educational function.

- **activeTab:** Supports interaction with the active Gemini tab when the user invokes the extension.
- **scripting:** Allows the extension to insert instructor-configured instructions into Gemini's input field.
- **Host access:** Supports operation on Google Gemini and retrieval of published course configurations from the designated Supabase service.

The extension's functionality is limited to launching instructor-guided AI learning activities.

## 7. Educational Research

Aspasia Launcher is being developed and evaluated for noncommercial educational research.

This extension does not itself record student research participation, conversations, or responses.

If a separate educational research study collects participant information, that collection should be described in the study's own consent materials and applicable research documentation.

## 8. Data Security

Aspasia Launcher uses HTTPS connections when retrieving published configurations from Supabase and operating with Google Gemini.

No software or online service can guarantee absolute security. Data processed by third-party services remains subject to those services' security practices.

## 9. Changes to This Policy

This privacy policy may be updated as Aspasia Launcher develops or its data practices change. Updates will be published in this repository with a revised date.

## 10. Contact

For questions about Aspasia Launcher or this privacy policy, contact:

**crlarsen@ncsu.edu**
