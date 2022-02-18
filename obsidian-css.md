/* My CSS snippets adjusting the Minimal theme for the Obsidian note-taking software the last 1% to fit my preferences. Many of these are copies or based on ideas shared by the kind commenters on the Obsidian forum. */

/* Reduce boldnes of text color for non-selected files in sidebar, to better visually highlight active files */
.nav-file-title,
.search-result-file-match {
  color: var(--text-faint);
}

/* Increase scrollbar width, so it's easier to see and get my cursor on quickly */
::-webkit-scrollbar {
  width:20px;
}

/* Adjust normal text appearance outside of headings & code to be more compact */
.cm-s-obsidian {
font-size: 15px;
line-height: 20px;
}

/* Remove unnecessary-to-me sidebar functions (Notes header & Search) */
.workspace-tab-container-inner {
display: none;
}

/* Condense line spacing in file explorer & avoid character-level word breaks */
.nav-file-title-content,
.search-result-file-title,
.search-result-file-match {
padding-top: 0 !important;
padding-bottom: 0 !important;
line-height: 110% !important;
word-break: keep-all;
}

/* Blockify cursor for quicker visbility of where it is */
.cm-cursor {
border-left-width: .3em !important;
visibility: visible !important;
}

/* Remove sidebar icons I don't use */
div[aria-label = "Change sort order"]{
  display: none;
}