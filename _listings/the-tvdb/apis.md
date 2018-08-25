---
name: The TVDB
x-slug: the-tvdb
description: TheTVDB.com is a community driven database of television shows. All content
  and images on the site have been contributed by the sites users; the site uses moderated
  editing to maintain its own standards. The database schema and website are open
  source under the GNU General Public License.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
x-kinRank: "7"
x-alexaRank: "0"
tags: Actors
created: "2018-08-24"
modified: "2018-08-24"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/actors/master/_listings/the-tvdb/apis.md
specificationVersion: "0.14"
apis:
- name: The TVDB
  x-api-slug: the-tvdb
  description: api-v2-targets-v1-functionality-with-a-few-minor-additions--the-api-is-accessible-via-httpsapi-thetvdb-com-and-provides-the-following-rest-endpoints-in-json-format-how-to-use-this-api-documentationyou-may-browse-the-api-routes-without-authentication-but-if-you-wish-to-send-requests-to-the-api-and-see-response-data-then-you-must-authenticate-1--obtain-a-jwt-token-by-posting--to-the-login-route-in-the-authentication-section-with-your-api-key-and-credentials-1--paste-the-jwt-token-from-the-response-into-the-jwt-token-field-at-the-top-of-the-page-and-click-the-add-token-button-you-will-now-be-able-to-use-the-remaining-routes-to-send-requests-to-the-api-and-get-a-response-language-selectionlanguage-selection-is-done-via-the-acceptlanguage-header--at-the-moment-you-may-only-pass-one-language-abbreviation-in-the-header-at-a-time--valid-language-abbreviations-can-be-found-at-the-languages-route--authenticationauthentication-to-use-the-api-is-similar-to-the-howto-section-above--users-must-post-to-the-login-route-with-their-api-key-and-credentials-in-the-following-format-in-order-to-obtain-a-jwt-token-apikeyapikeyusernameusernameuserkeyuserkeynote-that-the-username-and-key-are-only-required-for-the-user-routes--the-users-key-is-labled-account-identifier-in-the-account-section-of-the-main-site-the-token-is-then-used-in-all-subsequent-requests-by-providing-it-in-the-authorization-header--the-header-will-look-like-authorization-bearer-yourjwttoken--currently-the-token-expires-after-24-hours--you-can-get-the-refresh-token-route-to-extend-that-expiration-date-versioningyou-may-request-a-different-version-of-the-api-by-including-an-accept-header-in-your-request-with-the-following-format-acceptapplicationvnd-thetvdb-vversion--this-documentation-automatically-uses-the-version-seen-at-the-top-and-bottom-of-the-page-
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Televisions, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/actors/master/_listings/the-tvdb/seriesidactors-get-openapi.md
- name: The TVDB
  x-api-slug: the-tvdb
  description: TheTVDB.com is a community driven database of television shows. All
    content and images on the site have been contributed by the sites users; the site
    uses moderated editing to maintain its own standards. The database schema and
    website are open source under the GNU General Public License.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/thetvdb.jpeg
  humanURL: http://thetvdb.com
  baseURL: https://api-dev.thetvdb.com//
  tags: Actors
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/actors/master/_listings/the-tvdb/openapi.md
x-common:
- type: x-api-gallery
  url: http://the.open.movie.database.api.gallery.streamdata.io
- type: x-api-stack
  url: http://the.tvdb.stack.network
- type: x-documentation
  url: https://api.thetvdb.com/swagger
- type: x-website
  url: http://thetvdb.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---