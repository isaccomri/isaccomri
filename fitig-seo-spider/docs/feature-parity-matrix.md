# Feature Parity Matrix

Installed version: 0.1.45. Full parity has NOT been achieved.

Partial tested coverage: 186/206 = 90.3%; counts ENGINE_TESTED, PARTIAL_TESTED and PARTIAL_OFFLINE_TESTED entries, not full equality. Requested 90% stop threshold reached.

311 automated tests; 608 installed native checks. See release-0.1.45.md and milestone-90-coverage.md.

| Status | Features |
|---|---:|
| BLOCKED_SECURITY_REVIEW | 1 |
| ENGINE_TESTED | 1 |
| IMPLEMENTED_UI_UNVERIFIED | 1 |
| MODEL_TESTED_UI_UNVERIFIED | 1 |
| PARTIAL_OFFLINE_TESTED | 4 |
| PARTIAL_TESTED | 181 |
| PENDING | 7 |
| PENDING_EVIDENCE | 6 |
| SOURCE_UNVERIFIED | 4 |

| ID | Feature | Status |
|---|---|---|
| FITIG-001 | Top menu bar | PARTIAL_TESTED |
| FITIG-002 | Crawl address toolbar | PARTIAL_TESTED |
| FITIG-003 | Category tabs | PARTIAL_TESTED |
| FITIG-004 | Result table | PARTIAL_TESTED |
| FITIG-005 | Column reorder | PARTIAL_TESTED |
| FITIG-006 | Sort columns | PARTIAL_TESTED |
| FITIG-007 | Search records | PARTIAL_TESTED |
| FITIG-008 | URL selection | PARTIAL_TESTED |
| FITIG-009 | Lower URL details | PARTIAL_TESTED |
| FITIG-010 | Inlinks pane | PARTIAL_TESTED |
| FITIG-011 | Outlinks pane | PARTIAL_TESTED |
| FITIG-012 | Headers pane | PARTIAL_TESTED |
| FITIG-013 | Headings pane | PARTIAL_TESTED |
| FITIG-014 | Issues pane | PARTIAL_TESTED |
| FITIG-015 | Progress and queued count | PARTIAL_TESTED |
| FITIG-016 | Overview counts | PARTIAL_TESTED |
| FITIG-017 | Dark and light modes | PARTIAL_TESTED |
| FITIG-018 | English and partial Hebrew RTL | PARTIAL_TESTED |
| FITIG-019 | Keyboard shortcuts | PARTIAL_TESTED |
| FITIG-020 | Context menu | PARTIAL_TESTED |
| FITIG-021 | Saved crawl path | PARTIAL_TESTED |
| FITIG-022 | Resume controls | PARTIAL_TESTED |
| FITIG-023 | HTTP fetching | PARTIAL_TESTED |
| FITIG-024 | HTTPS fetching | PARTIAL_TESTED |
| FITIG-025 | Bounded response body | PARTIAL_TESTED |
| FITIG-026 | Request timeout | SOURCE_UNVERIFIED |
| FITIG-027 | HTTP status | PARTIAL_TESTED |
| FITIG-028 | Response headers | PARTIAL_TESTED |
| FITIG-029 | Redirect destination | PARTIAL_TESTED |
| FITIG-030 | Redirect loop termination | PARTIAL_TESTED |
| FITIG-031 | Origin scope | PARTIAL_TESTED |
| FITIG-032 | Fragment stripping | PARTIAL_TESTED |
| FITIG-033 | Crawl depth observation | PARTIAL_TESTED |
| FITIG-034 | Delay between requests | PARTIAL_TESTED |
| FITIG-035 | Robots agent selection | PARTIAL_TESTED |
| FITIG-036 | Robots allow and disallow | PARTIAL_TESTED |
| FITIG-037 | Robots wildcard and end anchor | PARTIAL_TESTED |
| FITIG-038 | Persistent frontier | PARTIAL_TESTED |
| FITIG-039 | Incremental SQLite observations | PARTIAL_TESTED |
| FITIG-040 | Resume committed crawl | PARTIAL_TESTED |
| FITIG-041 | Stop marker | PARTIAL_TESTED |
| FITIG-042 | HTML links | PARTIAL_TESTED |
| FITIG-043 | Script resources | PARTIAL_TESTED |
| FITIG-044 | Stylesheet resources | PARTIAL_TESTED |
| FITIG-045 | Image resources | PARTIAL_TESTED |
| FITIG-046 | XML sitemap loc discovery | PARTIAL_TESTED |
| FITIG-047 | Page titles | PARTIAL_TESTED |
| FITIG-048 | Meta descriptions | PARTIAL_TESTED |
| FITIG-049 | H1 | PARTIAL_TESTED |
| FITIG-050 | H2 | PARTIAL_TESTED |
| FITIG-051 | H3 | PARTIAL_TESTED |
| FITIG-052 | H4 | PARTIAL_TESTED |
| FITIG-053 | H5 | PARTIAL_TESTED |
| FITIG-054 | H6 | PARTIAL_TESTED |
| FITIG-055 | Canonical URL | PARTIAL_TESTED |
| FITIG-056 | Robots meta directives | PARTIAL_TESTED |
| FITIG-057 | X-Robots-Tag | PARTIAL_TESTED |
| FITIG-058 | Hreflang declarations | PARTIAL_TESTED |
| FITIG-059 | Image URL and alt | PARTIAL_TESTED |
| FITIG-060 | Anchor text | PARTIAL_TESTED |
| FITIG-061 | Link rel | PARTIAL_TESTED |
| FITIG-062 | JSON-LD payloads | PARTIAL_TESTED |
| FITIG-063 | Source text word count | PARTIAL_TESTED |
| FITIG-064 | Exact body hash | SOURCE_UNVERIFIED |
| FITIG-065 | Response size | PARTIAL_TESTED |
| FITIG-066 | Response elapsed time | PARTIAL_TESTED |
| FITIG-067 | Missing title | PARTIAL_TESTED |
| FITIG-068 | Missing description | PARTIAL_TESTED |
| FITIG-069 | Missing H1 | PARTIAL_TESTED |
| FITIG-070 | Multiple H1 | PARTIAL_TESTED |
| FITIG-071 | Missing image alt | PARTIAL_TESTED |
| FITIG-072 | Invalid JSON-LD syntax | PARTIAL_TESTED |
| FITIG-073 | HTTP error issue | PARTIAL_TESTED |
| FITIG-074 | Plain HTTP issue | PARTIAL_TESTED |
| FITIG-075 | Exact duplicate bodies | SOURCE_UNVERIFIED |
| FITIG-076 | Inlink relationships | PARTIAL_TESTED |
| FITIG-077 | Broken internal link report | PARTIAL_TESTED |
| FITIG-078 | Crawl comparison added URLs | PARTIAL_TESTED |
| FITIG-079 | Crawl comparison removed URLs | PARTIAL_TESTED |
| FITIG-080 | Crawl comparison changed fields | PARTIAL_TESTED |
| FITIG-081 | Response status groups | PARTIAL_TESTED |
| FITIG-082 | Missing metadata | PARTIAL_TESTED |
| FITIG-083 | Duplicate metadata | PARTIAL_TESTED |
| FITIG-084 | Multiple headings | PARTIAL_TESTED |
| FITIG-085 | HTTP URL filter | PARTIAL_TESTED |
| FITIG-086 | Missing HSTS | PARTIAL_TESTED |
| FITIG-087 | Missing CSP | PARTIAL_TESTED |
| FITIG-088 | Missing image alt filter | PARTIAL_TESTED |
| FITIG-089 | Noindex filter | PARTIAL_TESTED |
| FITIG-090 | Nofollow filter | PARTIAL_TESTED |
| FITIG-091 | Low word count | PARTIAL_TESTED |
| FITIG-092 | Has hreflang | PARTIAL_TESTED |
| FITIG-093 | Raw JSON-LD view | PARTIAL_TESTED |
| FITIG-094 | Read-only load | PARTIAL_TESTED |
| FITIG-095 | Project seed guard | PARTIAL_TESTED |
| FITIG-096 | Queued count query | PARTIAL_TESTED |
| FITIG-097 | CSV report | PARTIAL_TESTED |
| FITIG-098 | HTML report | PARTIAL_TESTED |
| FITIG-099 | Typed XLSX report | PARTIAL_TESTED |
| FITIG-100 | CLI JSONL progress | PARTIAL_TESTED |
| FITIG-101 | Tauri command bridge | PARTIAL_TESTED |
| FITIG-102 | Default timestamped project | SOURCE_UNVERIFIED |
| FITIG-103 | Refuse replacement of existing project | PARTIAL_TESTED |
| FITIG-104 | Chromium JavaScript rendering | PARTIAL_TESTED |
| FITIG-105 | Source versus rendered DOM | PARTIAL_TESTED |
| FITIG-106 | Rendered screenshots | PARTIAL_TESTED |
| FITIG-107 | Console diagnostics | PARTIAL_TESTED |
| FITIG-108 | JavaScript links after render | PARTIAL_TESTED |
| FITIG-109 | Custom CSS extraction | PARTIAL_TESTED |
| FITIG-110 | Custom XPath extraction | PARTIAL_TESTED |
| FITIG-111 | Custom regex extraction | PARTIAL_TESTED |
| FITIG-112 | Custom search | PARTIAL_TESTED |
| FITIG-113 | Custom JavaScript | PARTIAL_TESTED |
| FITIG-114 | GA4 OAuth and mapping | PARTIAL_OFFLINE_TESTED |
| FITIG-115 | Search Console OAuth and mapping | PARTIAL_OFFLINE_TESTED |
| FITIG-116 | URL Inspection API | PARTIAL_TESTED |
| FITIG-117 | PageSpeed Insights API | PARTIAL_OFFLINE_TESTED |
| FITIG-118 | API quotas and retries | PARTIAL_TESTED |
| FITIG-119 | API credential storage | PARTIAL_TESTED |
| FITIG-120 | Site Structure directory tree | MODEL_TESTED_UI_UNVERIFIED |
| FITIG-121 | Crawl tree | PARTIAL_TESTED |
| FITIG-122 | Force-directed graph | PARTIAL_TESTED |
| FITIG-123 | Graph focus and export | PARTIAL_TESTED |
| FITIG-124 | Post-crawl link scoring | PARTIAL_TESTED |
| FITIG-125 | Near-duplicate similarity | PARTIAL_TESTED |
| FITIG-126 | Canonical chain validation | PARTIAL_TESTED |
| FITIG-127 | Canonical indexability | PARTIAL_TESTED |
| FITIG-128 | Hreflang return-link validation | PARTIAL_TESTED |
| FITIG-129 | Structured data schema rules | PARTIAL_TESTED |
| FITIG-130 | Structured data rich-result checks | PARTIAL_TESTED |
| FITIG-131 | Sitemap membership reconciliation | PARTIAL_TESTED |
| FITIG-132 | Sitemap index recursion | PARTIAL_TESTED |
| FITIG-133 | Orphan URL analysis | PARTIAL_TESTED |
| FITIG-134 | XML sitemap generation | PARTIAL_TESTED |
| FITIG-135 | External URL HTTP checking | PARTIAL_TESTED |
| FITIG-136 | External tab complete records | PARTIAL_TESTED |
| FITIG-137 | Include and exclude rules | PARTIAL_TESTED |
| FITIG-138 | URL rewriting | PARTIAL_TESTED |
| FITIG-139 | Subdomain scope | PARTIAL_TESTED |
| FITIG-140 | Configurable max depth | PARTIAL_TESTED |
| FITIG-141 | Concurrency limit | PARTIAL_TESTED |
| FITIG-142 | Retry policy | PARTIAL_TESTED |
| FITIG-143 | Custom user-agent and headers | PARTIAL_TESTED |
| FITIG-144 | HTTP authentication | PARTIAL_TESTED |
| FITIG-145 | Form authentication | PENDING |
| FITIG-146 | Proxy settings | PARTIAL_TESTED |
| FITIG-147 | Cookie jar | PARTIAL_TESTED |
| FITIG-148 | Session configuration profiles | PARTIAL_TESTED |
| FITIG-149 | List mode | PARTIAL_TESTED |
| FITIG-150 | Scheduling | PARTIAL_TESTED |
| FITIG-151 | CLI batch automation | PARTIAL_TESTED |
| FITIG-152 | Filtered-table export | PARTIAL_TESTED |
| FITIG-153 | Bulk inlinks export | PARTIAL_TESTED |
| FITIG-154 | Bulk outlinks export | PARTIAL_TESTED |
| FITIG-155 | Export all competitor report variants | PENDING |
| FITIG-156 | Export charts | PARTIAL_TESTED |
| FITIG-157 | Google Sheets export | PENDING |
| FITIG-158 | Accessibility engine | PARTIAL_TESTED |
| FITIG-159 | Spelling and grammar | PARTIAL_TESTED |
| FITIG-160 | N-grams | PARTIAL_TESTED |
| FITIG-161 | Semantic search | PENDING |
| FITIG-162 | AMP validation | PARTIAL_TESTED |
| FITIG-163 | Pagination validation | PARTIAL_TESTED |
| FITIG-164 | Mobile audit | PARTIAL_TESTED |
| FITIG-165 | Link metrics providers | PARTIAL_OFFLINE_TESTED |
| FITIG-166 | AI providers | PENDING |
| FITIG-167 | Schema migration policy | PARTIAL_TESTED |
| FITIG-168 | Large crawl virtualization | PARTIAL_TESTED |
| FITIG-169 | Crash recovery stress test | PARTIAL_TESTED |
| FITIG-170 | Pane resizing | PARTIAL_TESTED |
| FITIG-171 | Column widths persistence | PARTIAL_TESTED |
| FITIG-172 | Full Hebrew translation | PENDING |
| FITIG-173 | Native file dialogs | PARTIAL_TESTED |
| FITIG-174 | Accessibility keyboard audit | PARTIAL_TESTED |
| FITIG-175 | Windows installed-app smoke test | PARTIAL_TESTED |
| FITIG-176 | NSIS installer build | PARTIAL_TESTED |
| FITIG-177 | Signed installer | PENDING |
| FITIG-178 | Installed version identification | PARTIAL_TESTED |
| FITIG-179 | Complete installed menu tree | PENDING_EVIDENCE |
| FITIG-180 | Every installed column | PENDING_EVIDENCE |
| FITIG-181 | Every installed tab filter | PENDING_EVIDENCE |
| FITIG-182 | Every settings default | PENDING_EVIDENCE |
| FITIG-183 | Every export variant | PENDING_EVIDENCE |
| FITIG-184 | Licensed workflow availability | PENDING_EVIDENCE |
| FITIG-185 | Competitor fixture output comparison | PARTIAL_TESTED |
| FITIG-186 | Database initialization snapshot | ENGINE_TESTED |
| FITIG-187 | Feature availability view | IMPLEMENTED_UI_UNVERIFIED |
| FITIG-188 | Directory tree visualisations | PARTIAL_TESTED |
| FITIG-189 | 3D crawl and directory diagrams | PARTIAL_TESTED |
| FITIG-190 | Inlink anchor text word cloud | PARTIAL_TESTED |
| FITIG-191 | Body text word cloud | PARTIAL_TESTED |
| FITIG-192 | Content cluster diagram | PARTIAL_TESTED |
| FITIG-193 | Visualisation browser regression suite | PARTIAL_TESTED |
| FITIG-194 | Single click branch expansion | PARTIAL_TESTED |
| FITIG-195 | Rich graph node tooltip | PARTIAL_TESTED |
| FITIG-196 | Readable Hebrew sitemap XML | PARTIAL_TESTED |
| FITIG-197 | Resource category inventories | PARTIAL_TESTED |
| FITIG-198 | Filtered current-table CSV | PARTIAL_TESTED |
| FITIG-199 | Default content area excludes navigation | PARTIAL_TESTED |
| FITIG-200 | Import and reconcile XML URL sitemap | PARTIAL_TESTED |
| FITIG-201 | Stored raw and rendered source reprocessing | PARTIAL_TESTED |
| FITIG-202 | Native installer compiler investigation | BLOCKED_SECURITY_REVIEW |
| FITIG-203 | HTML base href resolution | PARTIAL_TESTED |
| FITIG-204 | Browser final URL and crawl scope | PARTIAL_TESTED |
| FITIG-205 | HTML declared charset decoding and Hebrew Windows-1255 | PARTIAL_TESTED |
| FITIG-206 | Explicit remote XML and gzip sitemap retrieval | PARTIAL_TESTED |
