grunt-octave
============
Grunt plugin to start octave as task.

### Usage Examples

```js

module.exports = function(grunt) {
	grunt.loadNpmTasks('grunt-octave');

	grunt.initConfig({
		octave: {
			options: [],
			#{your_task_name1}: {
				src: "#{your_src_path}",
				options: ['--silent']
			},
			#{your_task_name2}: {
				src: "#{your_src_path}",
			}
		}
	});
};
```