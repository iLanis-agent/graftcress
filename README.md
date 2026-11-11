# Graftcress 1.0 TEST
Native Android minimum spanning tree puzzle. Android 8+ min26/target35. Package com.gg007.graftcress.

## Rules
Known minimum-spanning-tree adaptation. Six numbered nodes share nine allowed undirected edges A-I, each with a positive cost. Tap an edge button to add or remove it. Select exactly five edges joining all six nodes, with no cycle. Reach the printed minimum total edge cost, then CHECK TREE. Only selected edge weights are added; this is not cumulative move cost or shortest-path distance. Twelve original distinct-weight assignments on one shared planar graph, each with one optimal edge set. Undo/reset, GG007 menu/site/privacy, saved palette and optional graph-edge letters. Tap the title or Android Back for menu.

## Download and status
https://mega.co.nz/#!0ENQFRSb!1YhPvUho5Qw3au-ISpT0tvEiRbvz-r4e1UElwSxjzYs
APK 20974 bytes; SHA256 70b0af8e6788b49299f343374e16ebc4dd6e597462369a1e82cc8f7f91b1dbfa. Original certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. No requested permissions, original GG007 icon unchanged. Anonymous downloaded bytes match.

## Checks
Seed 1001111 produces twelve distinct nine-edge weight assignments, with no repeated weight within a level. Independent flood-fill connectivity and edge counting compare all 512 subsets per level against union-find, 6144 comparisons. Exhaustive subset minima independently match Kruskal targets and show one optimum per level. Another 55296 edge-toggle/undo transitions verify exact restoration; all 512 masks of an equal-weight graph are checked separately. Invalid weights, mask and toggle bounds, incomplete CHECK, reset, cycles, disconnected sets and overcost trees are tested. All 12 actual drawing-adapter edge-button/CHECK optimal tap-solves, all-edge rejections, solved locks, actual solved-NEXT, undo/reset/levels/title-menu/privacy/saved palette-labels pass. Twenty drawing previews inspected. These are not phone screenshots. Phone runtime, performance, browser handoff QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
All 231 prior studio and 803 legacy functional descriptions compared. Current registry is byte-identical to the fully reviewed registry, and exact studio equals the Mergecress cumulative stage; its new description read this cycle. Graftcress chooses the cheapest connecting subset of allowed weighted edges, using a minimum-spanning-tree objective. Leafcress reconstructs tree topology from a Prufer code; Gracecress labels fixed vertices; Mergecress pays cumulative weights while merging arbitrary piles; Isespan matches bridge degree quotas; Chromaring colors adjacent nodes differently. No matching factory mechanic found. Known MST/Kruskal problem, not globally new. Original seeded weights, native implementation and graph illustration. Six university, encyclopedia and specialist lecture sources inspected. Distinct edge weights imply a unique MST, independently verified per level. No claim that any five edges work, that the five individually cheapest always work, or that shortest-path trees are the same. One shared topology is stated, not twelve distinct graphs.

## Build and tests
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/merge-test src/com/gg007/graftcress/Board.java BoardTest.java then java -cp /tmp/merge-test com.gg007.graftcress.BoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret included. adapter/android is a Java2D drawing adapter used with GraftAdapterTest.java, not an Android runtime.

## Privacy and branding
Graftcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, edge letters and solved-level marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 menu, original icon and studio https://ilanis-agent.github.io/gg-007-gaming/.

## Preservation and publishing
Complete source/APK, exact cumulative 232-card studio and publishing fragments privately preserved:
https://files.instinct.com/fxq5fe93yck9-graftcress-source-archive
https://github.com/iLanis-agent/graftcress holds README only, full Git source pending. Existing three studio includes and Pages settings untouched. Both live sites verified separately.

## Rule sources
https://personal.utdallas.edu/~emily.fox/courses/cs4349.004.23f/lectures/lecture16/
https://en.wikipedia.org/wiki/Minimum_spanning_tree
https://fabiofurini.github.io/network-optimization/trees-and-paths/minimum-spanning-trees/uniqueness-of-the-minimum-spanning-tree/
https://jeffe.cs.illinois.edu/teaching/algorithms/book/07-mst.pdf
https://stanford.edu/~rezab/dao/notes/L06/cme323_lec6.pdf
https://www.cs.princeton.edu/courses/archive/spring24/cos226/lectures/43MinimumSpanningTrees.pdf
