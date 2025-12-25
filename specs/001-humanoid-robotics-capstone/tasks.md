---

description: "Task list for UI/Theme Update and GitHub Link Integration"
---

# Tasks: UI/Theme Update and GitHub Link Integration

**Input**: User request for updating UI and theme, removing X/Twitter icons, and adding GitHub link.
**Prerequisites**: Existing Docusaurus project configuration.

## Format: `[ID] [P?] [Story?] Description`

- **[P]**: Can run in parallel (different files, no dependencies)
- **[Story]**: Which user story this task belongs to (e.g., US1, US2, US3)
- Include exact file paths in descriptions

## Phase: UI/Theme Updates and Social Link Modifications

**Purpose**: To update the site's UI/theme, remove X/Twitter icons, and integrate the new GitHub profile link into the Docusaurus project's configuration wherever GitHub references exist.

- [ ] T001 [P] Update `href` for GitHub link in `themeConfig.navbar.items` in `docusaurus.config.js` to `https://github.com/Ayesha-joyo`.
- [ ] T002 [P] Update `href` for GitHub link in `themeConfig.footer.links` in `docusaurus.config.js` to `https://github.com/Ayesha-joyo`.
- [ ] T003 [P] Update `docs.editUrl` in `docusaurus.config.js` to `https://github.com/Ayesha-joyo/humanoid-robotics-book/tree/main/`.
- [ ] T004 [P] Update `organizationName` in `docusaurus.config.js` to `Ayesha-joyo`.
- [ ] T005 [P] Remove X/Twitter link and label from `themeConfig.footer.links.items` in `docusaurus.config.js`.
- [ ] T006 [P] Update author links in `blog/authors.yml` to point to `https://github.com/Ayesha-joyo` if applicable.
- [ ] T007 Verify updated GitHub links and removed X/Twitter icons by running local Docusaurus server (`npm run start` or `npm run serve`) and checking the navigation bar, footer, and edit links on documentation pages.

---

## Dependencies & Execution Order

### Phase Dependencies

- **UI/Theme Updates and Social Link Modifications**: No dependencies - can start immediately.

### Parallel Opportunities

- Tasks T001-T006 can be executed in parallel as they modify different parts of the configuration.

---

## Implementation Strategy

### Incremental Delivery

1.  Complete tasks T001-T006 to update configuration and remove X/Twitter links.
2.  Complete T007 for verification.

---

## Notes

- This `tasks.md` is specifically for updating UI/theme elements and integrating the new GitHub profile link.
- Manual verification (T007) is critical to ensure all links are correctly updated and X/Twitter icons are removed.