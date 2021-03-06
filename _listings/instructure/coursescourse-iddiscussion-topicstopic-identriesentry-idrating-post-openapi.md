---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Courses API Rate entry
  description: Rate entry.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/discussion_topics:
    get:
      summary: List discussion topics
      description: List discussion topics.
      operationId: list-discussion-topics
      x-api-path-slug: coursescourse-iddiscussion-topics-get
      parameters:
      - in: query
        name: only_announcements
        description: Return announcements instead of discussion topics
      - in: query
        name: order_by
        description: Determines the order of the discussion topic list
      - in: query
        name: scope
        description: Only return discussion topics in the given state(s)
      - in: query
        name: search_term
        description: The partial title of the discussion topics to match and return
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
    post:
      summary: Create a new discussion topic
      description: Create a new discussion topic.
      operationId: create-a-new-discussion-topic
      x-api-path-slug: coursescourse-iddiscussion-topics-post
      parameters:
      - in: query
        name: allow_rating
        description: If true, users will be allowed to rate entries
      - in: query
        name: assignment
        description: To create an assignment discussion, pass the assignment parameters
          as ansub-object
      - in: query
        name: attachment
        description: A multipart/form-data form-field-style attachment
      - in: query
        name: delayed_post_at
        description: If a timestamp is given, the topic will not be published until
          that time
      - in: query
        name: discussion_type
        description: The type of discussion
      - in: query
        name: group_category_id
        description: If present, the topic will become a group discussion assigned
          to the group
      - in: query
        name: is_announcement
        description: If true, this topic is an announcement
      - in: query
        name: lock_at
        description: If a timestamp is given, the topic will be scheduled to lock
          at thenprovided timestamp
      - in: query
        name: message
        description: no description
      - in: query
        name: only_graders_can_rate
        description: If true, only graders will be allowed to rate entries
      - in: query
        name: pinned
        description: If true, this topic will be listed in the u201cPinned Discussionu201d
          section
      - in: query
        name: podcast_enabled
        description: If true, the topic will have an associated podcast feed
      - in: query
        name: podcast_has_student_posts
        description: If true, the podcast will include posts from students as well
      - in: query
        name: position_after
        description: By default, discussions are sorted chronologically by creation
          date, youncan pass the id of another topic to have this one show up after
          the othernwhen they are listed
      - in: query
        name: published
        description: Whether this topic is published (true) or draft state (false)
      - in: query
        name: require_initial_post
        description: If true then a user may not respond to other replies until that
          user hasnmade an initial reply
      - in: query
        name: sort_by_rating
        description: If true, entries will be sorted by rating
      - in: query
        name: title
        description: no description
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
  /courses/{course_id}/discussion_topics/reorder:
    post:
      summary: Reorder pinned topics
      description: Reorder pinned topics.
      operationId: reorder-pinned-topics
      x-api-path-slug: coursescourse-iddiscussion-topicsreorder-post
      parameters:
      - in: query
        name: order[]
        description: The ids of the pinned discussion topics in the desired order
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Reorder
  /courses/{course_id}/discussion_topics/topic_id:
    delete:
      summary: Delete a topic
      description: Delete a topic.
      operationId: delete-a-topic
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-id-delete
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
    get:
      summary: Get a single topic
      description: Get a single topic.
      operationId: get-a-single-topic
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-id-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
    put:
      summary: Update a topic
      description: Update a topic.
      operationId: update-a-topic
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-id-put
      parameters:
      - in: query
        name: allow_rating
        description: If true, users will be allowed to rate entries
      - in: query
        name: assignment
        description: To create an assignment discussion, pass the assignment parameters
          as ansub-object
      - in: query
        name: delayed_post_at
        description: If a timestamp is given, the topic will not be published until
          that time
      - in: query
        name: discussion_type
        description: The type of discussion
      - in: query
        name: group_category_id
        description: If present, the topic will become a group discussion assigned
          to the group
      - in: query
        name: is_announcement
        description: If true, this topic is an announcement
      - in: query
        name: lock_at
        description: If a timestamp is given, the topic will be scheduled to lock
          at thenprovided timestamp
      - in: query
        name: message
        description: no description
      - in: query
        name: only_graders_can_rate
        description: If true, only graders will be allowed to rate entries
      - in: query
        name: pinned
        description: If true, this topic will be listed in the u201cPinned Discussionu201d
          section
      - in: query
        name: podcast_enabled
        description: If true, the topic will have an associated podcast feed
      - in: query
        name: podcast_has_student_posts
        description: If true, the podcast will include posts from students as well
      - in: query
        name: position_after
        description: By default, discussions are sorted chronologically by creation
          date, youncan pass the id of another topic to have this one show up after
          the othernwhen they are listed
      - in: query
        name: published
        description: Whether this topic is published (true) or draft state (false)
      - in: query
        name: require_initial_post
        description: If true then a user may not respond to other replies until that
          user hasnmade an initial reply
      - in: query
        name: sort_by_rating
        description: If true, entries will be sorted by rating
      - in: query
        name: title
        description: no description
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
  /courses/{course_id}/discussion_topics/topic_id/entries:
    get:
      summary: List topic entries
      description: List topic entries.
      operationId: list-topic-entries
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-identries-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Entries
    post:
      summary: Post an entry
      description: Post an entry.
      operationId: post-an-entry
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-identries-post
      parameters:
      - in: query
        name: attachment
        description: a multipart/form-data form-field-style attachment
      - in: query
        name: message
        description: The body of the entry
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Entries
  /courses/{course_id}/discussion_topics/topic_id/entries/{entry_id}/rating:
    post:
      summary: Rate entry
      description: Rate entry.
      operationId: rate-entry
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-identriesentry-idrating-post
      parameters:
      - in: query
        name: rating
        description: A rating to set on this entry
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Entries
      - Entry
      - Id
      - Rating
  /courses/{course_id}/discussion_topics/topic_id/entries/{entry_id}/read:
    delete:
      summary: Mark entry as unread
      description: Mark entry as unread.
      operationId: mark-entry-as-unread
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-identriesentry-idread-delete
      parameters:
      - in: query
        name: forced_read_state
        description: A boolean value to set the entry&#39;s forced_read_state
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Entries
      - Entry
      - Id
      - Read
    put:
      summary: Mark entry as read
      description: Mark entry as read.
      operationId: mark-entry-as-read
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-identriesentry-idread-put
      parameters:
      - in: query
        name: forced_read_state
        description: A boolean value to set the entry&#39;s forced_read_state
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Entries
      - Entry
      - Id
      - Read
  /courses/{course_id}/discussion_topics/topic_id/entries/{entry_id}/replies:
    get:
      summary: List entry replies
      description: List entry replies.
      operationId: list-entry-replies
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-identriesentry-idreplies-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Entries
      - Entry
      - Id
      - Replies
    post:
      summary: Post a reply
      description: Post a reply.
      operationId: post-a-reply
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-identriesentry-idreplies-post
      parameters:
      - in: query
        name: attachment
        description: a multipart/form-data form-field-style attachment
      - in: query
        name: message
        description: The body of the entry
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Entries
      - Entry
      - Id
      - Replies
  /courses/{course_id}/discussion_topics/topic_id/entries/{id}:
    delete:
      summary: Delete an entry
      description: Delete an entry.
      operationId: delete-an-entry
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-identriesid-delete
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Entries
      - Id
    put:
      summary: Update an entry
      description: Update an entry.
      operationId: update-an-entry
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-identriesid-put
      parameters:
      - in: query
        name: message
        description: The updated body of the entry
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Entries
      - Id
  /courses/{course_id}/discussion_topics/topic_id/entry_list:
    get:
      summary: List entries
      description: List entries.
      operationId: list-entries
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-identry-list-get
      parameters:
      - in: query
        name: ids[]
        description: A list of entry ids to retrieve
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Entry
      - List
  /courses/{course_id}/discussion_topics/topic_id/read:
    delete:
      summary: Mark topic as unread
      description: Mark topic as unread.
      operationId: mark-topic-as-unread
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-idread-delete
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Read
    put:
      summary: Mark topic as read
      description: Mark topic as read.
      operationId: mark-topic-as-read
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-idread-put
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Read
  /courses/{course_id}/discussion_topics/topic_id/read_all:
    delete:
      summary: Mark all entries as unread
      description: Mark all entries as unread.
      operationId: mark-all-entries-as-unread
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-idread-all-delete
      parameters:
      - in: query
        name: forced_read_state
        description: A boolean value to set all of the entries&#39; forced_read_state
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Read
    put:
      summary: Mark all entries as read
      description: Mark all entries as read.
      operationId: mark-all-entries-as-read
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-idread-all-put
      parameters:
      - in: query
        name: forced_read_state
        description: A boolean value to set all of the entries&#39; forced_read_state
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Read
  /courses/{course_id}/discussion_topics/topic_id/subscribed:
    delete:
      summary: Unsubscribe from a topic
      description: Unsubscribe from a topic.
      operationId: unsubscribe-from-a-topic
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-idsubscribed-delete
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Subscribed
    put:
      summary: Subscribe to a topic
      description: Subscribe to a topic.
      operationId: subscribe-to-a-topic
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-idsubscribed-put
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - Subscribed
  /courses/{course_id}/discussion_topics/topic_id/view:
    get:
      summary: Get the full topic
      description: Get the full topic.
      operationId: get-the-full-topic
      x-api-path-slug: coursescourse-iddiscussion-topicstopic-idview-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Discussion
      - Topics
      - Topic
      - Id
      - View
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---