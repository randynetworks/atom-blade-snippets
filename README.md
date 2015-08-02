#Blade templating snippets for Atom

Laravel 5 blade snippets! useful snippets for the Blade Templating Engine to use in Atom.

Converted from [blade-snippets for sublime](https://github.com/dev4dev/blade-snippets)
using the [sublime to atom](https://github.com/james2doyle/sublime-to-atom-snippets) script.

##Usage

These snippets will trigger only in `*.blade.php` files.

Type any snippet and hit TAB to receive incredible results!.

Checkout the [Available blade snippets.](#Available snippets)

snippet: !! + TAB = incredible result: {!! `$var` !!}

I recommend [this Blade language Package for Atom](https://atom.io/packages/language-blade) to be able to take full advantage of the Blade Templating Engine in this amazing editor.

##Available snippets

| Shortcut  | Result |
|-----------|--------|
| **}}** _or_ **echo** _or_	**print**	| {{ `$var` }} |
| **!!**	_or_ **uecho** _or_	**uprint** | {!! `$var` !!}	|
| **ext**	_or_ **extends** | @extends('`name`')	|
| **sec**	_or_ **section** | @section('`name`') <br /><br /> @endsection |
| **sshow**	_or_ **secs** | @section('`name`') <br /><br /> @show |
| **yl** _or_ **yield**	| @yield('`section`') |
| **par**	_or_ **parent**	| @parent	|
| inc		| @include('`view.name`', `['some' => 'data']`)  |
| if		| @if (`condition`) <br /><br /> @endif   |
| ife		| @if (`condition`) <br /><br /> @else <br /><br /> @endif  |
| foreach	| @foreach(`$array` as `$element`) <br /><br /> @endforeach  |
| fore		| @forelse (`$array` as `$element`) <br /><br /> @endforelse  |
| for		| @for (`$i` = `0`; `$i` `<` `…`; `$i++`) <br /><br /> @endfor  |
| each		| @each ('`item.view`', $`items`, '`item`', '`empty.view`')
| trans		| {!! trans('`language.line`') !!}	|
| route		| {!! route('`name`') !!}	|
| asset		| {!! asset('`path`') !!}	|
| action	| {!! link_to_action('`Controller@method`') !!}	|
| while		| @while (`condition`) <br /><br /> @endwhile  |
| unless	| @unless (`condition`) <br /><br /> @endunless  |
| choice	| @choice('`language.line`', $`number`)  |
| comment	| {{-- `comment` --}}	|
| lang		| @lang('`language.line`', `['variable => 'replacement']`)  |


##Disclaimer

Feel free to contribute!

As of today, i am a complete noob at making atom packages, if there is any error,
suggestion, improvement, etc, to point or make, feel free to do so.
